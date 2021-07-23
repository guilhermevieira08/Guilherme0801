<h1>Olá! </h1><h2>Sou o Guilherme Vieira</h2>

<style>
    body{
        background-color: antiquewhite;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    
    }
    .violao{
        width: 500px;
        height: 500px;
    }
    .first_ball {
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #998235;
        width: 195px;
        height: 195px;
        position: relative;
        border-radius: 50%;
    }
    .second_ball {
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #998235;
        width: 170px;
        height: 170px;
        border-radius: 50%;
        position: relative;
        margin-top: -172px;
        margin-left: -99px;
    }
    .mastro {
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #1A4341;
        width: 167px;
        height: 38px;
        /* border-radius: 50%; */
        position: relative;
        margin-top: -107px;
        z-index: -1;
        margin-left: -252px;
    }
    .quadrado {
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        align-items: center;
        background-color: #998235;
        width: 85px;
        height: 53px;
        border-radius: 11px;
        /* border-radius: 50%; */
        position: relative;
        margin-top: -45px;
        z-index: -1;
        margin-left: -332px;
    }
    .content{
        margin: 50%;
    }
    .over{
        width: 70px;
        height: 70px;
        border-radius: 50%;
        background-color: #1A4341;
        border: 10px solid #F3AC3C;
        z-index: 1;
    }
    .ret {
        width: 12px;
        height: 85px;
        background-color: #1A4341;
        border-radius: 20px;
    }
    .risco_1{
        width: 43px;
        height: 12px;
        border-radius: 12px;
        background-color: #1A4341;
    }
    .risco_2{
        width: 43px;
        height: 12px;
        border-radius: 12px;
        background-color: #1A4341;
    }
</style>
<body>
    <div class="violao">
        <div class="content">
            <div class="first_ball">
                <div class="ret"></div>
            </div>
            <div   div class="second_ball">
                <div class="over"></div>
            </div>
            <div div class="mastro">
            </div>
            <div div class="quadrado">
                <div class="risco_1"></div>
                <div class="risco_2"></div>
            </div>
        </div>
    </div>
</body>
