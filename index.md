main .secaoSobre {
    width:95%;
    margin: 10px;;
    /* border: 1px solid rgb(94, 196, 221);; */

}
main .secaoSobre .flex {
    
    width:100%;
    /* padding: 10px; */
    display: flex;
    flex-direction: column;
    align-items: center;
}
main .secaoSobre .flex .flex-col{
    display:flex;
    flex-direction: column;
    flex-wrap: wrap;
    align-items:center;
    width: 70%;
    padding: 10px;
    margin: 20px;
   
 
}
/* main .secaoSobre .flex .flex-col h2 {



} */

main .secaoSobre .flex .flex-col p {
    width: 100%;
    font-size:var(--font-text);
    font-family:'Lato', sans-serif;
    margin-top: 50px;
    margin-bottom: 20px;
    line-height:1.5;
    color: var(--gray-color);
    
}
main .secaoSobre .flex .flex-col span {
    color:#818181;
    line-height:1.5;
    font-size:var(--font-text);
    font-family:'Lato', sans-serif;
}
main .secaoSobre .flex .flex-col button {
    font-size:var(--font-text);
    font-family:'Lato', sans-serif;
    font-weight:400;
    width: 60%;
    height: 40px;
    margin-top:30px;
    border-radius: 0.25rem;
    color: var(--gray-color);
    border: 1px solid #999797;
    outline: 0;
}
main .secaoSobre .flex .flex-col figure {
    /* border:1px solid yellow; */
    margin:10px;
    width: 65%;
    height:120px;
    display:flex;
    justify-content:center;
}
main .secaoSobre .flex .flex-col figure img{
    width: 90%;


}

#fig-python {
    width: 180%;
    height: 100%;
}

main .secaoSobre .flex .flex-col figure figcaption {
    display:none;
}

main .secaoSobre .flex .flex-col--modifier {
    width:65%;
    margin:-30px;
    color:var(--light-gray);
    line-height:1.1;
}

main .secaoSobre .flex .flex-col--modifier h2 {
    text-align:center;
    color: var(--gray-color);
   
}
main .secaoSobre .flex .flex-col--modifier ul {
    list-style-type: disc;
    padding: 20px;
}
main .secaoSobre .flex .flex-col--modifier  ul li{
    font-size: var(--font-text);
}