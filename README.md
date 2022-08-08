# kargaon
 A view of my Village


@import url('https://fonts.googleapis.com/css2?family=Gotu&family=Nunito&display=swap');

:root{
    --primary-color: #2dd4bf;
    --dark-gray: #4b5563;
    --off-white: #e2e8f0;
}

body{
    font-family: 'Gotu', sans-serif;
    font-family: 'Nunito', sans-serif;
    margin: 0;
    background-color: whitesmoke;
}

hr{
    margin: 2rem 0rem;
}

/* container */
.container{
    padding-left: 1rem;
    padding-right: 1rem;
}

.container-fluid{

}

.container-center{
    max-width: 600px;
    margin: auto;
}

/* links */
.link{
    text-decoration: none;
    padding: 0.5rem 1rem;
}

.link-primary{
    background-color: var(--primary-color);
    border-radius: 0.5rem;
    color: white;
}

.link-secondary{
    color: #14b8a6;
    border: 1px solid #14b8a6;
    border-radius: 0.5rem;
}

/* TIP - look into BEM naming conventions for CSS */

/* lists */
.list-non-bullet{
    list-style: none;
}

.list-item-inline{
    display: inline;
    padding: 0rem 0.5rem;
}

/* navigation */
.navigation{
    background-color: var(--primary-color);
    color: var(--dark-gray);
    padding: 1rem;
    border-bottom-left-radius: 1rem;
}

.navigation .nav-brand{
    font-weight: bolder;
    font-size: x-large;
}

.navigation .link{
    color: var(--dark-gray);
}

.navigation .nav-pills{
    text-align: right;
}

.navigation .link-active{
    font-weight: bold;
}

/* header */
.hero{
    padding: 2rem;
}

.hero .hero-ing{
    max-width: 350px;
    display: block;
    margin: auto;
}

.hero .hero-heading{
    text-align: center;
    padding-top: 1rem;
    color: var(--dark-gray);
}

.hero .hero-heading .heading-inverted{
    color: var(--primary-color);
}

/* section */
.section{
    padding: 2rem;
}

.section h1{
    text-align: center;
}

.ow{
    background-color: var(--off-white);
}

/* footer */
.footer{
    background-color: var(--primary-color);
    padding: 2rem 0rem;
    text-align: center;
    color: white;
    border-bottom-right-radius: 1rem;
}

.footer .footer-header{
    font-size: large;
    font-weight: bold;
}

.footer .link{
    color: white ;
}

.footer ul{
    padding-inline-start: 0px;
}
