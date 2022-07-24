<template>
    <div class="container">
        <div id="title">Christmas Q25</div>
        <div class="subtitle">- 당신의 1년을 정리하는 25개의 질문 -</div>
        <div id="Registration">축하하는 느낌의 일러스트</div>
        <div style="color: white;">
            생성이 완료되었어요 :)<br>
            <div id="usermail"><a :href="email">{{email}}</a></div>
            메일함을 확인해주세요!
        </div>
        <div><button type="button" onclick="" class="btn">바로가기</button></div>
    </div>
</template>

<script>


export default {
  name: 'App',
  data(){
    return{
        email : 'user@gmail.com'
    }
  },
  components: {

  }
}
</script>

<style>
@font-face {
    font-family: 'NanumSquareRound';
    src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_two@1.0/NanumSquareRound.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}

@import url('https://fonts.googleapis.com/css2?family=Sorts+Mill+Goudy&display=swap');

.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #920000;
    width: 360px; height: 640px;
    margin: 0 auto;
}

.btn {
    margin: 7px;
    background-color: white;
    border: none;
    border-radius: 3px;
    width: 120px; height: 30px;
    cursor: pointer;

    font-weight: bold;
}

#title {
    color: #FFF500;
    font-family: 'Sorts Mill Goudy', serif;
    font-size: 50px;
    margin-top: 50px;
}

#logo {
    color: black;
    width: 50px;
    padding: 60px;
    border: 1px solid black;
    margin: 40px;
    padding-top: 70px;
    padding-bottom: 70px;
    text-align : center;

    background-color: white;
}

#introductionBox {
    border: 1px solid black;
    width: 300px;
    background-color: white;
    margin: 25px;
}

#Registration {
    color: black;
    width: 50px;
    padding: 60px;
    border: 1px solid black;
    margin: 40px;
    text-align: center;

    background-color: white;
}

#Backbtn {
    background-color:rgba(0,0,0,0);
    color: #0D86FE;
    font-weight: bold;
    border-color: transparent;
    border: none;
    cursor: pointer;
}

.subtitle {
    color: white;
}

#password {
    width: 170px; height: 30px;
    border-radius: 3px;
    border: none;
    margin: 5px;
    text-align: center;
}

body {
    font-family: 'NanumSquareRound';
}

#usermail {
    text-decoration-line: underline;
    color: blue;
    text-align: center;
    cursor: pointer;
}
</style>
