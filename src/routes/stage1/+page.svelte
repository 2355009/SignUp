<script lang="ts">

    class Data{
        title:String;
        text:String;
        isCheck:Boolean;
        constructor(title:String,text:String){
            this.title=title;
            this.text=text;
            this.isCheck=true;
        }
    }
export let datas=[
    new Data(
        '개인정보의 처리 목적',
        '< 안영진 >(\'www.nicesite.com\'이하 \'회원가입\')은(는) 다음의 목적을 위하여 개인정보를 처리합니다. 처리하고 있는 개인정보는 다음의 목적 이외의 용도로는 이용되지 않으며 이용 목적이 변경되는 경우에는 「개인정보 보호법」 제18조에 따라 별도의 동의를 받는 등 필요한 조치를 이행할 예정입니다.<br><br>1. 재화 또는 서비스 제공<br>콘텐츠 제공을 목적으로 개인정보를 처리합니다.'
    ),
    new Data(
        '개인정보의 처리 및 보유 기간',
        '① < 안영진 >은(는) 법령에 따른 개인정보 보유·이용기간 또는 정보주체로부터 개인정보를 수집 시에 동의받은 개인정보 보유·이용기간 내에서 개인정보를 처리·보유합니다.<br><br>② 각각의 개인정보 처리 및 보유 기간은 다음과 같습니다.<br><br>1.<재화 또는 서비스 제공><br><재화 또는 서비스 제공>와 관련한 개인정보는 수집.이용에 관한 동의일로부터<지체없이 파기>까지 위 이용목적을 위하여 보유.이용됩니다.<br>보유근거 :<br>관련법령 :<br>예외사유 :'
    ),
    new Data(
        '처리하는 개인정보의 항목',
        '① < 안영진 >은(는) 다음의 개인정보 항목을 처리하고 있습니다.<br><br>1< 재화 또는 서비스 제공 ><br>필수항목 : 이름, 로그인ID, 비밀번호'
    ),
    new Data(
        '개인정보의 파기절차 및 파기방법',
        '① < 안영진 > 은(는) 개인정보 보유기간의 경과, 처리목적 달성 등 개인정보가 불필요하게 되었을 때에는 지체없이 해당 개인정보를 파기합니다.<br><br>② 정보주체로부터 동의받은 개인정보 보유기간이 경과하거나 처리목적이 달성되었음에도 불구하고 다른 법령에 따라 개인정보를 계속 보존하여야 하는 경우에는, 해당 개인정보를 별도의 데이터베이스(DB)로 옮기거나 보관장소를 달리하여 보존합니다.<br>1. 법령 근거 :<br>2. 보존하는 개인정보 항목 : 계좌정보, 거래날짜<br><br>③ 개인정보 파기의 절차 및 방법은 다음과 같습니다.<br>1. 파기절차<br>< 안영진 > 은(는) 파기 사유가 발생한 개인정보를 선정하고, < 안영진 > 의 개인정보 보호책임자의 승인을 받아 개인정보를 파기합니다.'
    ),
    new Data(
        '정보주체와 법정대리인의 권리·의무 및 그 행사방법에 관한 사항',
        '① 정보주체는 안영진에 대해 언제든지 개인정보 열람·정정·삭제·처리정지 요구 등의 권리를 행사할 수 있습니다.<br>② 제1항에 따른 권리 행사는안영진에 대해 「개인정보 보호법」 시행령 제41조제1항에 따라 서면, 전자우편, 모사전송(FAX) 등을 통하여 하실 수 있으며 안영진은(는) 이에 대해 지체 없이 조치하겠습니다.<br>③ 제1항에 따른 권리 행사는 정보주체의 법정대리인이나 위임을 받은 자 등 대리인을 통하여 하실 수 있습니다.이 경우 “개인정보 처리 방법에 관한 고시(제2020-7호)” 별지 제11호 서식에 따른 위임장을 제출하셔야 합니다.<br>④ 개인정보 열람 및 처리정지 요구는 「개인정보 보호법」 제35조 제4항, 제37조 제2항에 의하여 정보주체의 권리가 제한 될 수 있습니다.<br>⑤ 개인정보의 정정 및 삭제 요구는 다른 법령에서 그 개인정보가 수집 대상으로 명시되어 있는 경우에는 그 삭제를 요구할 수 없습니다.<br>⑥ 안영진은(는) 정보주체 권리에 따른 열람의 요구, 정정·삭제의 요구, 처리정지의 요구 시 열람 등 요구를 한 자가 본인이거나 정당한 대리인인지를 확인합니다.'
    ),
    new Data(
        '개인정보의 안전성 확보조치에 관한 사항',
        '< 안영진 >은(는) 개인정보의 안전성 확보를 위해 다음과 같은 조치를 취하고 있습니다.<br><br>1. 개인정보 취급 직원의 최소화 및 교육<br>개인정보를 취급하는 직원을 지정하고 담당자에 한정시켜 최소화 하여 개인정보를 관리하는 대책을 시행하고 있습니다.'
    ),
    new Data(
        '개인정보를 자동으로 수집하는 장치의 설치·운영 및 그 거부에 관한 사항',
        '안영진 은(는) 정보주체의 이용정보를 저장하고 수시로 불러오는 ‘쿠키(cookie)’를 사용하지 않습니다.'
    ),
    new Data(
        '개인정보 보호책임자에 관한 사항',
        '① 안영진 은(는) 개인정보 처리에 관한 업무를 총괄해서 책임지고, 개인정보 처리와 관련한 정보주체의 불만처리 및 피해구제 등을 위하여 아래와 같이 개인정보 보호책임자를 지정하고 있습니다.<br><br>▶ 개인정보 보호책임자<br>성명 :안영진<br>직책 :제작자<br>직급 :제작자<br>연락처 :01093170312, anyoungjin0106@kbu.ac.kr<br>※ 개인정보 보호 담당부서로 연결됩니다.<br><br>▶ 개인정보 보호 담당부서<br>성명 :안영진<br>직책 :제작자<br>직급 :제작자<br>연락처 :01093170312, anyoungjin0106@kbu.ac.kr<br>② 정보주체께서는 안영진 의 서비스(또는 사업)을 이용하시면서 발생한 모든 개인정보 보호 관련 문의, 불만처리, 피해구제 등에 관한 사항을 개인정보 보호책임자 및 담당부서로 문의하실 수 있습니다. 안영진 은(는) 정보주체의 문의에 대해 지체 없이 답변 및 처리해드릴 것입니다.    '
    ),
    new Data(
        '개인정보 처리방침 변경',
        '① 이 개인정보처리방침은 2023년 1월 1부터 적용됩니다.<br>② 이전의 개인정보 처리방침은 아래에서 확인하실 수 있습니다.'
    )
]
export function Check(){
    let result:boolean=false;
    
    datas.forEach(element => {
        console.log(element.title+" : "+element.isCheck);
        if(((element.isCheck==true)&&(element.title!=datas[4].title))||
        ((element.isCheck==false)&&(element.title==datas[4].title))){
            result=true;
        }
    });
    console.log(result);
    if(result){
        alert('다시 확인 해주세요');
        window.location.href="./";
    }else{
        alert('로그인을 시작하겠습니다');
        window.location.href="./stage2";
    }
}
</script>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>회원가입</title>
</head>
<body>
    {#each datas as data,index}
    <div class="card">
  <div class="card-header">
    제 {index+1}조
  </div>
  <div class="card-body">
    <h5 class="card-title">{@html data.title}</h5>
    <p class="card-text">{@html data.text}</p>
  </div>
</div>
<div style="float: right;">
    <input type="checkbox" bind:checked={data.isCheck}>동의 
    {#if index+1!=5}
    안 
    {:else}
    &nbsp;
    {/if}
     합니다
</div>
<br>
    {/each}
    <center>
<button type="button" class="btn btn-success" style="background-color:#3D0454" on:click={Check}>다음으로</button>
    </center>
</body>