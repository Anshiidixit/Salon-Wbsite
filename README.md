# Salon-Wbsite
@import url('https://fonts.googleapis.com/css2?family=Dela+Gothic+One&family=Inter:wght@400;500;600&display=swap');

:root {
    --bg1: #151828;
    --bg2: #1B1F34;
    --body: #959DCC;
    --brand: #FFAB76;
    --white: #fff;
}

body {
    font-family: "Inter",'Segoe UI',Tahoma,Geneva, Verdana, sans-serif;
    color: var(--body);
    line-height: 1.8;
    background-color: var(--bg1);
}

h1,h2,h3,h4,h5,h6{
    font-family: "Dela Gothic One",'Segoe UI',Tahoma,Geneva, Verdana, sans-serif;
    color: white;
}

a{
    color: var(--body);
    text-decoration: none;
    transition: all 0.4s ease;
}

a:hover{
    color: var(--brand)
}

.link-more{
    display: inline-flex;
    align-items: center;
    font-size: 13px;
    font-weight: 600;
    text-transform: uppercase;
    left: 1px;
}

.link-more.icon{
    transition: all 0.4s ease;
}

.link-more:hover .icon{
    transform: translate(8px);
}

img{
    width: 100%;
}

section{
    padding-top: 160px;
    padding-bottom: 160px;
    position: relative;
}

/* INTRO */
.intro{
    margin-bottom: 60px;
}

.intro h1{
    margin-top: 16px;
    margin-bottom: 16px;
}

.intro h6{
    color: var(--brand);
}

.intro p{
    max-width: 500px;
    margin:auto;
}

.cta-btns{
    margin-top: 60px;
}




/* NAVBAR */
.navbar{
    background: linear-gradient(toright ,#1B1F34,right#1B1F34)

}

.navbar .navbar-nav .nav-link.active(
    color: var(--brand);
)
.navbar-brand{
    font-family: "Inter",'Segoe UI',Tahoma,Geneva, Verdana, sans-serif;
    font-size: 32px ;
}

/* HERO */
#hero{
    background: linear-gradient(toright ,#1B1F34,right#1B1F34),url(C:\Users\Anshika\OneDrive\Pictures);
        background-size: cover;
        background-position: center;
        
#hero p{
    margin-top: 24px;
    margin-bottom: 24px;
}

/* BTN */
.btn{
    padding: 16px 36px;min-height: 100vh;
        display: flex;
        align-items: centre;
}

    font-family: "Inter",'Segoe UI',Tahoma,Geneva, Verdana, sans-serif;
    transition: all 0.4s ease;
    border-radius: 0;
}

.btn-brand{
    background-color: var(--brand);
}

.btn-bramd:hover{
    background-color: transparent;
    color: var(--brand);
    border-color: var(--brand);
}

.btn-outline-brand:hover{
    background-color: var(--brand);
}


/* about  */
#about{
    position: relative;
}

#about::after{
    content: "";
    width: 25%;
    height: 100%;
    background-color:var(--brand);
    position: absolute
    top: 0;
    left: 0;
    z-index
}

#about h6{
    color:var(--brand);
}

#about h1{
    margin-top: 16px;
    margin-bottom: 24px;
}

#about .signature{
    content: "";
    width: 25%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    background: var(--brand);
    z-index: -1;
}

/* service */
#services{
    background: var(--bg2);
}

#services  .service  .content{
    padding: 32px

}
#service .service p{
    margin: 18px;
    margin-bottom: 18px;
}

/* MILESTONE */
#milestone{
    background: linear-gradient(toright ,rgba(27, 31, 52, 0.8),rgba(27, 31, 52, 0.8)),url(../img/cover_2.jpg);
        background-size: cover;
        background-position: centre;

} 

#milestone h1{
    color: var(--brand);
}

/* features */

.feature{
    display: flex;
}
.feature .iconfeature{
   font-size: 38px;
   color: var(--brand);
   line-height: 1;
   margin-right: 16px;
}

.feature p{
    font-size: 14px;
    margin-top: 16px;
    margin-bottom: 16px;
}

.social-links a{
    width: 42px;
    height: 48px;
    background-color: var(--bg2);
    display: flex;
    align-items: center;
    justify-content: center;
}

/* social icons */

.social-links a:hover{
    background-color: var(--brand);
    color: var(--bg2);
}

/* Team member */
{
    .positionteam-member{
        position: relative
    }
}
.team-member{
    position: relative;
    background-color: var(--bg2);
    }
}

.team-member .social-links{
    position: absolute;
    top: 0px;
    right: 30px;
    transition: all 0.4s ease;
    opacity: 0;
}

.team-member:hover .social-links{
    opacity: 1;
    top: 30px;
}

/* reviews */
#reviews{
    background-color: var(--bg2);
}

.reviev{
    padding: 32px;
    background-color: : var(--bg2); 
}

.review .icon{
    width: 42px;
    height: 42px;
    display: flex;
    align-items: centre;
    justify-content: center;
    background-color: var(-- var(--brand));
    color:var(--bg1);
    border-radius:100px;
    position: absolute;
    right: 32px;
    

}
.review img{
    width: 70px;
    border-radius: 100px;
}

/* blog */

#blog{
    background-color: var(--bg2);
}
.blog-post {
    position: relative;
}

.blog-post .date{
    width: 100px;
    height: 100px;
    background-color: var(--brand);
    text-align: center;
    display: flex;
    align-items: centre;
    justify-content: center;
    position: absolute;
    top: 30px;
    left: 30px;
}

.blog-post  .day{
    font-size: 32px;
    line-height: 1;
    font-family: "dela gothic one",'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: var(--bg1);
}

.blog-post .year{
    color:var(--bg1);
}
/* booking */
#booking{
    background: linear-gradient(toright ,rgba(27, 31, 52, 0.8),rgba(27, 31, 52, 0.8)),url(../img/cover_2.jpg);
    background-size: cover;
    background-position: centre;
}

#bookinf form{
    background-color: var(--bg1);
    padding: 32px;
}

#booking form.form-control{
   background-color: var(--bg2);
   border-radius: 0;
   margin-top: 16px;
   border-color: var(--bg2);
   border: 2px solid var(--bg2);
   color: var(--body);
}

#booking form.form-control:focus {
    height: 58px;
}

#booking form.form-control:focus{
    box-shadow: none;
    border-left-color: var(--brand);
}
