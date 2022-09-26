<pre>
#container{
    display: grid;
    grid-template-columns: repeat(5,1fr);
    grid-auto-rows: auto;
}
#one,#two,#three,#four,#five,#six,#seven,#eight{
    background-color: aqua;
    color: white;
    font-size: xx-large;
    text-align: center;
    padding: 1rem;
}
#one{
    grid-area: 1/1/3/2;
}
#two{
    background-color:coral;
    grid-area: 1/2/1/5;
}
#three{
    background-color:limegreen;
    grid-area: 2/2/2/5;
}
#four{
    background-color:peru;
    grid-area: 1/5/3/6;
}
#five{
    background-color:palevioletred;
    grid-area: 3/1/3/3;
}
#six{
    background-color:violet;
    grid-area: 3/3/3/4;
}
#seven{
    background-color:plum;
    grid-area: 4/1/4/4;
}
#eight{
    background-color:purple;
    grid-area: 3/4/5/6;
}
</pre>
