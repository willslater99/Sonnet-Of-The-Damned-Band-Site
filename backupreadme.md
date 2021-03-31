/* 
/*------- Mobile Media Queries -------*/

@media only screen and (max-width: 600px) {

    /*------- Making Navbar Vertical on Mobile -------*/

.navbar-nav > li {
    display: inline-block;
    float: none;
}

.custom-toggler {
    margin-right: 3em;
}

#navbarmenu > ul {
    display: inline-flex;
    text-align: center;
    margin-right: 80px;
}

.navbar-toggler {
    margin-top: 1em;
}

#band-logo {
    height: 3em;
    width: 15em;
    display: block;
    margin: 0 auto;
    margin-right: 2em;
}

.social-links {
    padding-bottom: 0px;
    padding-top: 12px;
}

.social-links li a i {
    width: 46px;
    height: 46px;
    margin: 0 10px;
    padding: 24px 0;
    border-radius: 25%;
    font-size: 2.6rem;
    line-height: 7px;
    text-align: center;
     color: black;
    background: white;
    transition: all 0.25s ease-in-out;
    -moz-transition: all 0.25s ease-in-out;
    -webkit-transition: all 0.25s ease-in-out;
    -o-transition: all 0.25s ease-in-out;
}

#social-desktop {
    display: none;
}

#social-mobile {
    display: block;
    margin-top: 20px;
}

/*------- Optimising Footer on Mobile -------*/

#legal-info {
    text-align: center;
    margin: 10px 20px 20px 0px;
}

.social-links-footer {
    display: none;
}

footer {
    min-height: 60px;
}

/*------- Index.html on Mobile -------*/

.news-and-new-release {
    min-height: 300px;
    min-width: 300px;
    font-size: 2.5rem;
}

.initial-container {
    height: 110vh
}

.jumbotron.about-the-band-jumbo {
    margin: 0;
    min-width: 350px;
}

.about-the-band-jumbo {
    background-color: rgba(0,0,0,.0);
    border-style: none;
    min-height: 300px;
    max-width: 350px;
    margin-right: 0px;
}

#small-band-photo {
    border-style: solid;
    border-width: 2px;
    border-color: black;
    max-width: 350px;
    max-height: 250px;
    display: block;
}

#about-the-band-small {
    max-width: 350px;
}

#band-info-mobile {
    display: block;
    margin: 0 auto;
}

#band-info-tablet {
    display: none;
}

.about-dividers {
    display: none;
}

.container-fluid.small-about-container {
    padding-left: 0;
    padding-right: 0;
}

/*------- News.html on Mobile -------*/

.news-sections {
    min-height: 500px;
    min-width: 300px;
    margin-right: 40px;
    margin-left: 40px;
    margin-top: 40px;
    margin-bottom: 40px;
}

.news-container {
    background-color: rgb(223, 223, 223);

    height: 320vh;
 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;

  display: flex;
  align-items: center;
  justify-content: center;

  position: relative;
}

/*------- Tour.html on Mobile -------*/

#tour-page-desktop {
    display: none;
}

#tour-page-mobile {
    display: inherit;
}


.tour-container {
    height: 210vh;
}


/*------- Merch.html on Mobile -------*/

.merch-container {
    height: 190vh;
}

.merch-sections {
    min-height: 350px;
    min-width: 350px;
    margin-right: 40px;
    margin-left: 40px;
    margin-top: 20px;
    margin-bottom: 40px;
}

#merch-page-tablet {
    display: none;
}

.product-images {
    width: 300px;
    height: 300px;
    margin: 0 auto;
}

.product-images img {
  max-width: 100%;
  max-height: 100%;
}

.merch-sections.product-images {
    margin: 0 auto;
}

/*------- About.html on Mobile -------*/


.band-info-column {
    max-width: 270px;
    margin: 0 auto;
}

#about-page-band-photo img {
    max-width: 280px;
    margin: 0 auto;
}

.member-photos {
    max-width: 85vw;
}
}

/*------- Tablet Media Queries -------*/


@media only screen and (min-width: 601px) and (max-width: 1050px) {

    /*------- Making Navbar Work On Tablet -------*/

.navbar-nav > li {
    display: inline-block;
    float: none;
    font-size: 3em;
    margin: 0 40px;
}

.navbar-brand {
    width: 300px;
    height: 50px;
}

#band-logo {
    width: 400px;
    height: 60px;
    margin-top: -8px;
    margin-right: 300px;
    margin-left: -50px;
}

.navbar-toggler {
    margin-right: 10px;
}


/*------- Index.html on Tablet -------*/

.initial-container {
    max-height: 170vh;
    min-height: 150vh;
}
.news-and-new-release {
    min-height: 40vh;
    min-width: 90vw;
    font-size: 1.5rem;
    margin-left: 5px;
    margin-right: 5px;
}

#band-info-desktop {
    display: none;
}

#band-info-tablet {
    display: inherit;
}

#small-band-photo-tablet {
    min-width: 400px;
    margin-bottom: 50px;
}

.about-the-band-home-header {
    margin-top: 50px;
}


.about-the-band-jumbo {
    padding-top: 0px;
    padding-bottom: 0px;
}

.about-jumbos {
    width: 80%;
    float: none;
    position: relative;
}

.col-md-4 {
    max-width: 75%;
}

.col-md-6 #about-the-band-small-tablet {
    max-width: 75%;
}

.about-dividers {
    display: none;
}

#about-the-band-home-text-tablet {
    margin: 25px 0;
    color: black;
}

/*------- News.html on Tablet -------*/

.news-sections {
    min-height: 400px;
    min-width: 200px;
    margin-right: 5px;
    margin-left: 5px;
    margin-top: 20px;
    margin-bottom: 20px;
    font-size: 2.4rem;
}

.news-container {
    background-color: rgb(223, 223, 223);

    max-height: 255vh;
    min-height: 235vh;
 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;

  display: flex;
  align-items: center;
  justify-content: center;

  position: relative;
}

#news-page-desktop {
    display: none;
}

#news-page-tablet {
    display: inherit;
}

/*------- Tour.html On Tablet -------*/

.tour-sections {
    min-height: 1080px;
}

.tour-container {
    height: 110vh;
}

/*------- merch.html On Tablet -------*/

#merch-tablet {
    display: inherit;
}

#merch-desktop {
    display: none;
}

.merch-container {
    height: 60vh;
}

.merch-sections {
    min-height: 300px;
    min-width: 300px;
    margin-right: 20px;
    margin-left: 20px;
    margin-top: 20px;
    margin-bottom: 20px;
}

#merch-page-tablet {
    display: none;
}

.product-images {
    width: 250px;
    height: 250px;
    margin: 0 auto;
}

.product-images img {
  max-width: 100%;
  max-height: 100%;
}

.merch-sections.product-images {
    margin: 0 auto;
}

/*------- about.html on Tablet-------*/

#about-band-desktop {
    display: none;
}

#about-the-band-text-tablet {
    font-size: 2.5em;
    margin: 0 auto;
}

#about-the-band-text-tablet-column-two {
    font-size: 2.5em;
    margin: 0 auto;
}

#about-page-band-photo-tablet img {
    max-width: 280px;
    margin: 0 auto;
}

#about-band-tablet {
    display: inherit;
}

.member-photos {
    max-width: 45vw;
}

#about-members-desktop {
    display: none;
}

#about-members-tablet {
    display: inherit;
}
}

 */
