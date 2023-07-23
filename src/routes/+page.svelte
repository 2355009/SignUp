<body>
    <center>
        <h1>회원가입</h1>
        <h2>잘못된 UI와 UX를 극복하라</h2>
        {#each Array(2) as i }
          <h1>&nbsp</h1>
        {/each}
        <h3>회원가입을 하시러면 <a href="./stage1">여기를</a> <fake on:click={()=>{alert('ㅋㅋ 속았죠 ㅋㅋㅋ');}}>눌러주세요</fake></h3>
    </center>
</body>
<style>
    a{
        color: black;
        text-decoration: none;
    }
    fake{
        color: blue;
        text-decoration:underline;
    }
</style>