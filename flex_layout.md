#container,#fiveSixSeven,#oneToFour , #fiveToEight{
display: flex;
}
#container{
    flex-direction: column;

}
.one,.two,.three,.four,.five,.six,.seven,.eight{
display: flex;
align-items: center;
justify-content: center;
}
#twoThree{
display: flex;
    flex-direction: column;
    flex: 1 1 50rem;
}
#fiveSix{
    display: flex;
    flex: 1 1 5rem;
}
#fiveSixSeven{
    flex-direction: column;
    flex: 1 1 15rem ;
}
#one,#two,#three,#four,#five,#six,#seven,#eight{
    color: white;
    font-size: xx-large;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-weight: bolder;
    text-align: center;
    padding: 1rem 0;
}
#one{
    background-color: #1ABC9C;
    flex: 0 1 25rem;
}
#two{
    background-color:#E67E22;
    flex: 1 1 5rem
}
#three{
    background-color:#27AE60;
    flex: 1 1 5rem
}
#four{
    background-color:#F39C12;
    flex: 1 1 20rem
}
#five{
    background-color:#3498DB;
    flex: 1 1 25rem
}
#six{
    background-color:#8E44AD;
    flex: 1 1 1rem
}
#seven{
    background-color:#2C3E50;
    flex: 1 1 5rem
}
#eight{
    background-color:#C0392B;
    flex: 1 1 
}
