:root {
	--dark: #374151;
	--darker: #1F2937;
	--darkest: #111827;
	--grey: #6B7280;
	--green: #25ff2c;
	--light: rgb(213, 213, 213);
}
body{
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;

}
.sec{
    width: 40vw;
    height: 60vh;
    background-color: var(--light);
    border-radius: 5vh;
    border: 3px solid greens;
    box-shadow: 0px 10px 10px var(--darker);
    overflow: scroll;
    transition: .5s;
}
.sec:hover{
    box-shadow: 0px 10px 50px var(--darkest);
}
.intake{
    display: flex;
    flex-direction: column;
    border-radius: 5vh;
    width: 90%;
    min-height:5vh;
    outline: none;
    margin:5vh auto;

    background-color: var(--light);
    transition: .4s;

}
.intake:focus{
    box-shadow: 0px 10px 20px var(--dark);
}
.list{
    display: flex;
    flex-direction: column;
}
.task{
    background-color:var(--dark);
    display:flex;
    align-items: center;
    width:80%;
    margin:1vh auto;
    border-radius: 5vh;
    min-height: 5vh;
    padding-left: 30px;
    letter-spacing: .1rem;
    transition: .4s;
}
.task:hover{
    box-shadow: 0px 0px 5px var(--grey);
}
.a{ 
    width: 67%;
    overflow-x:scroll;
    scroll-behavior: smooth;
    scrollbar-color: var(--pink);
    scrollbar-width: thin;
    word-wrap: break-word;
    display: flex;
    color: white;
    transition: 1s;
}

.b{
    width: 35%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.done{
    border: none;
    color: var(--green);
    background-color: transparent;
    text-shadow: 0 0 4px var(--green);
}
.remove{
    color: crimson;
    border: none;
    background-color: transparent;
}
.done:hover,
.remove:hover{
   color: #fff;
   cursor: pointer;
   text-shadow:0 0 5px  #ffffff;
   transition: .2s;
}
::-webkit-scrollbar {
    width: 13px;
    height: 3px;
}
::-webkit-scrollbar-track {
    box-shadow: inset 0 0 5px grey; 
    border-radius: 10px;
}
::-webkit-scrollbar-thumb {
    background-image:linear-gradient(45deg,var(--grey), var(--grey)); 
    border-radius: 10px;
}
# todo1
