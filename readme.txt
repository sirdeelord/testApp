/*the asteric selector(*) is used to affect all element on the web page*/


$value:#006699;
*{
    margin: 0;
    padding: 0;/*padding is as white space between the box*/
    box-sizing: border-box;/*this size the boxes of the web page*/
    position: relative;
}
.clearfix:after {
    content: "";
    display: table;
    clear: both;
}

body{
    font-family: Helvetica Neue;
    font-size: 18px;
}

h1, h2 {
    color: #00960b;    
}

h1{
    font-size: 40px;
    margin-bottom: 20px;/*this create margin-bottom for xter*/
}

h2{
    font-size: 25px;
    margin-bottom: 10px;
}

/*to style the the main <p>. call the class created in the html starting with .(dot) example: .main-text*/
.main-text {
    text-align: justify;
    margin-bottom: 20px;
    
}

.author-text {
    font-size: 22px;
    float: left;
    margin-top: 30px;
    margin-left: 10px;
}
.container {
    width: 1140px;
    /*short and clean way to declare of margin: top right buttom left*/
    margin: 20px auto 0 auto;
}

.blog-post {
    width: 75%;/*the percentage that the blog post is gonna take on the web page */
    float: left;/*with float an element can be push to the left or right*/
    padding-right: 30px;/*padding is as white space between the box*/
}

.other-posts {
    width: 25%;
    float: left;/*with float an element can be push to the left or right*/
}

.author-box {   
    padding-top: 20px;
    border-top: 1px solid #808080;/*this create a borderline on top of the author img*/
}

.other {
    margin-bottom: 40px;
}

.author-box img { 
    width:100px;
    height:100px;
    border-radius: 50%;
    float: left;
}

.blog-post img {
    height: 150px;
    width: auto;
}

.date {
    position: absolute;
    top: 10px;
    right: 30px;
}

/* last line*/
.other-posts{
    background-color: red;
    .other{
        background-color: blue;
    }
}