<template>
  <div >
    <div class ="top" style="background color :black">
   <div class="topnav">
  <a class="active" href="#home">ADMIN PANEL</a>
  <span class="icon"><i class="fa fa-envelope " style= "margin-left :10%; margin-top:10px" ></i>
  <span class ="align">6</span></span>
  <span class="icon"><i class="fa fa-envelope " style= "margin-left:10px" ></i>
  <span class ="align">6</span></span>
  <span class="icon"><i class="fa fa-envelope " style= "margin-left:10px" ></i>
  <span class ="align">6</span></span>
  <span class="topnav-right">
   <span class="icon"><i class="fa fa-envelope " style= " margin-top:10px" ></i>
  <span class ="align" style= "margin-right:50px">6</span></span>
</span>
</div>
</div>
 <div class="col-md-3 sidebar">
 <div class="menu1" > DASHBOARD<span class="menu2">Dashboard</span>
 </div>
 </div>
<div id="main">
   <nav>  <div class="menu"><a >Link 1</a></div>
       <div class="menu"><a >Link 1</a></div>
       <div class="menu"><a >Link 1</a></div>
        <div class="menu"><a >Link 1</a></div>
         <div class="menu"><a >Link 1</a></div>
          <div class="menu"><a >Link 1</a></div>
           <div class="menu"><a >Link 1</a></div>
              </nav>
           <article><h2>ADMIN DASHBOARD</h2>
           <div class="time-header" ></div>
           <div class="border"></div>
    <div class="flex-container">
  <div ><i style="font-size:42px;color:white;padding-bottom:5px" class="fa">&#xf1ee;</i>
  <div>Zero Issue</div>
  </div>
  <div><i style="font-size:42px;color:white;padding-bottom:5px" class="fa">&#xf201;</i>
  <div>40 in process</div>
  </div>
  <div> <i style="font-size:42px;color:white; padding-bottom:5px" class="fa">&#xf155;</i>
  <div>200 to be paid</div>
</div>
 <div> <i style="font-size:42px;color:white;padding-bottom:5px" class="fa">&#xf155;</i>
  <div  >200 to be recevied</div>
</div>
    </div>
  <div class="time-header" style="margin-bottom:20px" ></div>
  <section class="content">
    <div class="columns">
<aside class="sidebar-first">
        <table style="width :100%" >
  <tr>
    <th>##</th>
    <th>Fastname</th>
    <th>Lastname</th>
    <th>User name</th>
<th>user id</th>
</tr>
  <tr>
    <td>1</td>
    <td>Smith</td>
    <td>50</td>
    <td><button class="button" style="background-color:green">Smith</button></td>
    <td>50</td>
  </tr>
  <tr>
    <td>2</td>
   <td><button class="button" style="background-color:red">Smith</button></td>
    <td>50</td>
    <td>Smith</td>
    <td><button class="button" style="background-color:blue">50</button></td>
  </tr>
  <tr>
    <td>3</td>
    <td>Smith</td>
    <td>Smith</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>4</td>
    <td><button class="button" style="background-color:orange">Smith</button></td>
    <td>50</td>
   <td><button class="button" style= "background-color:lightblue">Smith</button></td>
    <td>50</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Smith</td>
    <td>50</td>
   <td><button class="button" style="background-color:red">Smith</button></td>
    <td>50</td>
  </tr>
  <tr>
    <td>6</td>
    <td><button class="button" style="background-color:blue">Smith</button></td>
    <td>50</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>7</td>
    <td>Smith</td>
    <td><button class="button" style="background-color:green">60</button></td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>8</td>
    <td>Smith</td>
    <td>50</td>
    <td>Smith</td>
    <td><button class="button" style="background-color:orange"> 50</button></td>
  </tr>
  <tr>
    <td>9</td>
    <td><button class="button" style="background-color:lightblue">Smith</button></td>
    <td>50</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  </table>
</aside>
      <aside class="sidebar-first1" >
      <table frame="box" width="320" height="80% " style="border: 1px solid lightblue">
  <tr bgcolor="lightblue">
    <th><i class="fa fa-bell" style="font-size:15px;color:black;padding-right:5px; margin-left:-250px"></i>Month</th>
    </tr>
    <table style="width:80%">
 <tr>
    <th>Firstname</th>
    </tr>
  <tr>
    <td><i style="font-size:24px" class="fa">&#xf23e;</i>Jill</td>
    </tr>
  <tr>
    <td>Eve</td>
   </tr>
  <tr>
    <td>John</td>
     </tr>
  <tr>
    <td>John</td>
    </tr>
  <tr>
    <td>John</td>
    </tr>
  <tr>
    <td>John</td>
     </tr>
  <tr>
    <td>John</td>
    </tr>
     <tr>
    <td>John</td>
    </tr>
  </table>
  <div id="example_4" >view All Alerts</div>
  </table>
      </aside>
    </div>
  </section>
</article>

</div>

  </div>

</template>

<script>
export default {
  data () {
    return {}
  }
}
</script>

<style scoped>
.topnav {
  overflow: hidden;
  background-color: rgb(11, 67, 99);
  border-bottom:  5px solid rgb(199, 194, 194);
}
.topnav a {
  float: left;
  color: #f2f2f2;
  /* text-align: center; */
  padding: 20px 16px;
  text-decoration: none;
  font-size: 20px;
}
.topnav-right
{
  float: right;
}
.icon{
color: white;
  font-size:28px;
  height:10px;
 margin-top: 30px;
}
.align{
  font-size:16px;
  margin-top: 50%;
}
.sidebar-first{
  width: 15%;
}
.menu{
  border-bottom: 3px solid gray;
 margin-top:20px;
 padding:3px;
 width:103%;
 color: white
}
.menu1{
padding:3px;
width:338px;
background-color:  rgb(199, 194, 194);
height:40px;
}
.menu2{
   /* background-color: white; */
  margin-left:105%;
  height:80px;
/* margin-top: 2px; */
}
.time-header
{
    border-bottom-color: black;
    border-bottom-width: 2px;
    border-bottom-style: solid;
}
#main {
  display: flex;
  /* flex: 1; */
}
#main > article {
  flex: 1;
   background: beiged;
   height: 200%;
   border-top: 8px rgb(199, 194, 194) solid;
   border-left: 10px rgb(199, 194, 194) solid;
   font-size: 12px;
}
#main > nav,
#main > aside {
  flex: 0 0 20vw;
  background: beige;
   border-top: 3px rgb(199, 194, 194) solid;
}
#main > nav {
  order: -1;
 height: 200%;
  background-color: rgb(11, 96, 117);
}
article, nav, aside {
  padding: 1em;
}
.flex-container {
  display: flex;
}
.flex-container > div {
  background-color: rgb(11, 96, 117);
  margin: 10px;
  padding: 20px;
  font-size: 20px;
  flex-basis: 196px;
  margin-left: 40px;
  margin-top: 20px;
  margin-bottom: 45px;
  color: white;
  height: 60px;
  text-align: center;
  margin-top: 20px;
}
.content {
  display: flex;
  flex: 1;
  color: #000;
}
.columns{
  display: flex;
  flex:1;
  height: 476px;
}
.sidebar-first{
  width: 80%;
  margin-left: 20px;
}
.sidebar-first1{
  width: 40%;
;
  margin-left: 20px;
}
table, th, td {
    border: 1px solid rgb(199, 194, 194);
    border-collapse: collapse;
    font-size: 15px;
    margin:22px;
}
th, td {
    padding: 10px;
}
.col{
  height: 300px;
  width:40%;
}
#example_4 {
  height: 32px;
    background-color: #2e7dce;
    position: static;
    margin-bottom: 4%;
    margin-left: 8%;
    margin-right: 8%;
    margin-top: 4px;
    text-align: center;
    padding:4px;
    color: white;
}
.button {
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: -7px -8px;
    cursor: pointer;
    height: 41px;
}
</style>
