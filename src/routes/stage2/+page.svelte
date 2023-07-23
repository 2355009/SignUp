
<script lang="ts">
 const passwordreg:RegExp=new RegExp('^[a-zA-Z0-9_]{8,12}$');
 const idreg:RegExp=new RegExp('^[ㄱ-힣_0-9]{8,12}$');
 let id:string="";
 let name:string="";
 let password:string='';
 function isCheck():void{
    if(idreg.test(id)&&passwordreg.test(password)){
        alert('로그인 완료');
        window.location.href="./ending";
    }
 }
</script>
<body>
    <form>
        
    <p class="form-label">이름{$username}</p>
    <input   id="inputPassword5" class="form-control" aria-labelledby="passwordHelpBlock" bind:value={name}>
    <h5>&nbsp;</h5>
    <p class="form-label">암호</p>
    <input type="password" id="inputPassword5" class="form-control" aria-labelledby="passwordHelpBlock" bind:value={password}>
    
    <h5>&nbsp;</h5>
    <p class="form-label">아이디</p>
    <input type="text" id="inputPassword5" class="form-control" aria-labelledby="passwordHelpBlock" bind:value={id}>
    
    <h5>&nbsp;</h5>
    <div id="passwordHelpBlock" class="form-text">
        아이디는 8글자 이상 12글자 이하로 하시고 한글, 밑줄(_), 숫자로만 이루어져야 합니다.<br>
        암호는 8글자 이상 12글자 이하로 하시고 영어, 밑줄(_), 숫자로만 이루어져야 합니다.
      </div>
      <h5>&nbsp;</h5>
    
<button type="reset" class="btn btn-success" style="background-color:#3D0454" on:click={()=>{
    alert('속았지?ㅋㅋ');
    }}>리셋</button>
<button type="button" class="btn btn-danger" on:click={isCheck}>제출</button>
    </form>
</body>