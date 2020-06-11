<template>
  <div>
    <div>
      <b-navbar toggleable="lg" type="dark" variant="light" style="color: gray; border-bottom: 0.4px solid lightgray;">
        <b-nav-item href="#">
        <a href="#">
          <i class="glyphicon glyphicon-th-large"></i>
        </a>
        </b-nav-item>

        <b-navbar-brand href="#" style="color: gray;">
        HaggleX_Webapp
        </b-navbar-brand>

        <b-nav-item href="#">
        <i class="glyphicon glyphicon-menu-right"></i>
        </b-nav-item>

        <b-navbar-brand href="#" style="color: gray;">
        Web 1920 - 5
        </b-navbar-brand>


        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
              <b-nav-item href="#">
                <hr>
              <span style="color: gray;">
              46.4%
              <i class="glyphicon glyphicon-chevron-down"></i>
              </span>
              <i class="glyphicon glyphicon-resize-full"></i>
              <i class="glyphicon glyphicon-question-sign"></i>
              <a href="#" style="color: gray;">
                Sign In
              </a>
            </b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>

    <!-- This is the begining of the form section below -->
    <div class="row">
    <div class="col-8" style="height: 600px; width: 600px; border: 0.4px solid lightgray; margin-top: 50px;">
      <br />
      <br />
      <div
        class="col-12"
        style="row height: 400px; width: 400px; margin: 0 auto;"
      >
      <div class="row">
      <!-- this is the left side of the form -->
        <div class="col-6 mh-100" style="width: 200px; height: 300px; border: 0.4px solid lightgray; border-top-left-radius: 15px; border-bottom-left-radius: 15px; background-color: #fff;">
          <br />
          <h3>Log In</h3>
          <input
            v-model="value"
            type="text"
            class="form-control text border-top-0 border-left-0 border-right-0"
            placeholder="Email Address"
          />
          <br />
          <br />
          <input
            v-model="value"
            type="Password"
            class="form-control text border-top-0 border-left-0 border-right-0"
            placeholder="password"
          />
          <br />
          <span style="font-size: 6px;">New User? Sign Up to get started</span>
          <b-button block style="background: rgb(48,8,77);
background: linear-gradient(90deg, rgba(48,8,77,1) 5%, rgba(48,8,77,1) 5%, rgba(48,8,77,1) 5%, rgba(48,8,77,1) 5%);">Login</b-button>
          <span style="font-size: 6px;">Need Help? &nbsp;<span style="font-size: 6px; color: gray;" disabled>Privacy</span>&nbsp;&nbsp;<span style="font-size: 6px; color: gray;" disabled>Terms & Policy</span></span>
          <br />
        </div>
        <!-- this is the right side of the form -->
        <div class="col-6" style="width: 200px; height: 300px; border-top-right-radius: 15px; border-bottom-right-radius: 15px; background: rgb(48,8,77);
background: linear-gradient(90deg, rgba(48,8,77,1) 5%, rgba(48,8,77,1) 5%, rgba(48,8,77,1) 5%, rgba(48,8,77,1) 5%);"></div>
        </div>
      </div>
    </div>
    <!-- The start of the right sidebar -->
    
    <div class="col-3" style="height: 700px; width: 600px;  border-left: 0.4px solid lightgray; border-right: 0.4px solid lightgray;">
    <br>
    <br>   
    <b-input-group>
    <b-form-input class="LoginInput" size="lg" placeholder="make a comment">
    </b-form-input>
    <b-input-group-append>
    <span class="input-group-text" title="Place a pin"><i class="glyphicon glyphicon-pushpin" style='font-size:36px'></i></span>
    </b-input-group-append>
    </b-input-group>
    <br>
    &nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp;<span class="input-group-span">Cancel</span>&nbsp; &nbsp;&nbsp; &nbsp;&nbsp;<span class="input-group-span">Submit</span>
    <div>
        <svg class="comment"  style="backgroung: #fff; color:  #fff; margin-top: 180px;" title="Click to collapse panel" id="S_IlluXdComments_72x56" xmlns="http://www.w3.org/2000/svg" width="200" height="100" viewBox="0 0 72 56"><path class="bubble-path" d="M44,18.75H19a.75.75,0,0,1,0-1.5H44a.75.75,0,0,1,0,1.5Z"></path><path class="bubble-path" d="M37,24.75H19a.75.75,0,0,1,0-1.5H37a.75.75,0,0,1,0,1.5Z"></path><path class="bubble-path" d="M23.00391,44.76465A2.00777,2.00777,0,0,1,21,42.7627V35H14a5.00588,5.00588,0,0,1-5-5V12a5.00588,5.00588,0,0,1,5-5H49a5.00588,5.00588,0,0,1,5,5V30a5.00588,5.00588,0,0,1-5,5H33.103l-8.65088,9.1377A1.99246,1.99246,0,0,1,23.00391,44.76465ZM14,9a3.00328,3.00328,0,0,0-3,3V30a3.00328,3.00328,0,0,0,3,3h8a.99974.99974,0,0,1,1,1v8.7627l8.94678-9.4502A1.00064,1.00064,0,0,1,32.67285,33H49a3.00328,3.00328,0,0,0,3-3V12a3.00328,3.00328,0,0,0-3-3Z"></path><path class="bubble-path" d="M47.99512,50.21582a1.98957,1.98957,0,0,1-1.46582-.64648L40.47559,43H32a6.9751,6.9751,0,0,1-2.334-.39941.99982.99982,0,0,1,.668-1.88477A4.97724,4.97724,0,0,0,32,41h8.91406a1.00164,1.00164,0,0,1,.73535.32227L48,48.21387V42a.99974.99974,0,0,1,1-1H59a3.00328,3.00328,0,0,0,3-3V24a3.00328,3.00328,0,0,0-3-3H56a1,1,0,0,1,0-2h3a5.00588,5.00588,0,0,1,5,5V38a5.00588,5.00588,0,0,1-5,5H50v5.21387a1.98808,1.98808,0,0,1-1.27246,1.86328A2.00831,2.00831,0,0,1,47.99512,50.21582Z"></path></svg></div>
       <div style="text-align: center;">
        <h5 style="font-size: 12px;">Got something to say?</h5>
        <span style="font-size: 8px;">Comment to start a discussion, make a note, or</span>
        <br>
         <span style="text-align: center; font-size: 8px;">annotat the artboard.</span>
         </div>
   </div>

    <!-- undrneath the website -->
    <div class="col-1" style="height: 700px; width: 600px;">
        <img   style="color:  #fff; margin-top: 30px;"  title="View Specs" src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBmaWxsPSIjNjY2IiBkPSJNMTksNiBDMTksNS40NDc4IDE4LjU1MjIsNSAxOCw1IEw1LDUgQzQuNDQ3OCw1IDQsNS40NDc4IDQsNiBMNCwxNSBDNCwxNS41NTIyIDQuNDQ3OCwxNi4wMDA5IDUsMTYuMDAyIEw4LDE2IEw4LjAwNDExNTk5LDIwLjM0MTM3ODUgQzguMDA0MTE1OTksMjAuNjE1OTc4NSA4LjMzOTIzNDc3LDIwLjczODU4OTMgOC41MjczMjg0OSwyMC41MzkwNDcyIEwxMi4wMDczLDE2LjAwNzggTDE4LDE2LjAwMTEgQzE4LjU1MjIsMTYuMDAwNSAxOSwxNS41NTIyIDE5LDE1IEwxOSw2IFoiLz4KPC9zdmc+Cg==">
        <div class="buttonContainer-37nqv" data-auto="specViewButton" tabindex="0"><div class="specView-2Dn54" tabindex="-1"><img src="data:image/svg+xml;base64,PHN2ZyBpZD0iU21vY2tfQ29kZV8xOF9OIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8cmVjdCBpZD0iQ2FudmFzIiB3aWR0aD0iMTgiIGhlaWdodD0iMTgiIGZpbGw9IiNmZjEzZGMiIG9wYWNpdHk9IjAiLz4KICA8cGF0aCBpZD0iUGF0aF8zNjEwNSIgZGF0YS1uYW1lPSJQYXRoIDM2MTA1IiBkPSJNOC4yMjYsMTQuNDczYS41LjUsMCwwLDEtLjQ4My4zNzFINy4yMjdhLjUuNSwwLDAsMS0uNDcyLS42NjZMOS43ODYsMi42OTNhLjUuNSwwLDAsMSwuNDgzLS4zN2guNWEuNS41LDAsMCwxLC40NzIuNjY1WiIgZmlsbD0iIzcwNzA3MCIvPgogIDxwYXRoIGlkPSJQYXRoXzM2MTA2IiBkYXRhLW5hbWU9IlBhdGggMzYxMDYiIGQ9Ik0xNy43NDYsOS41M2wtNC4wOTUsNC4xNmEuNS41LDAsMCwxLS43MTMsMGwtLjQ0Ni0uNDUzYS41LjUsMCwwLDEsMC0uN0wxNS45NzEsOSwxMi40OTIsNS40NjRhLjUuNSwwLDAsMSwwLS43bC40NDYtLjQ1NGEuNS41LDAsMCwxLC43MTMsMGw0LjA5NSw0LjE2QS43Ni43NiwwLDAsMSwxNy43NDYsOS41M1oiIGZpbGw9IiM3MDcwNzAiLz4KICA8cGF0aCBpZD0iUGF0aF8zNjEwNyIgZGF0YS1uYW1lPSJQYXRoIDM2MTA3IiBkPSJNLjI1NCw4LjQ3bDQuMS00LjE2MWEuNS41LDAsMCwxLC43MTMsMGwuNDQ2LjQ1NGEuNS41LDAsMCwxLDAsLjdMMi4wMjksOWwzLjQ3OSwzLjUzNWEuNS41LDAsMCwxLDAsLjdsLS40NDYuNDUzYS41LjUsMCwwLDEtLjcxMywwTC4yNTQsOS41M2EuNzYuNzYsMCwwLDEsMC0xLjA2WiIgZmlsbD0iIzcwNzA3MCIvPgo8L3N2Zz4K"></div></div>
        <div class="reportAbuse-mE4tV" tabindex="-1" data-auto="reportAbuseButton"><img  title="Report Abuse" src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjM3IDcxNyAxNC4zMDIgMTQuMjMyIj4KCTxwYXRoIGZpbGw9IiNiYmIiIGQ9Ik0zNy4wNjcsNzE4LjAwNmEuNzA4LjcwOCwwLDAsMSwxLjI4Mi0uNmw1Ljk3OCwxMi44MTlhLjcwOC43MDgsMCwwLDEtMS4yODIuNmwtNS45NzgtMTIuODE5bTYuNDEsNi44MjRjLS4yLS4zNDMtMy44MDctNy42ODUtMy44MDctNy43MjMsMS4xMTQtLjEyMSw0LjA3OC0uMTM2LDUuMzQ4LjYyM2EzMi40NzUsMzIuNDc1LDAsMCwxLDUuOTU2LjA1Yy40MTUuMDY1LjQzMi4yODcuMDY5LjVhMzYuNTA3LDM2LjUwNywwLDAsMC03LjU2Niw2LjU1eiIvPgo8L3N2Zz4K"></div>
    </div>
    <div class="navButtons-1Qqr7"><div class="navButton-2FYM- homeButton-25MiB"><button data-auto="homeBtn" style="outline: none;"><span role="img" class="SVGInline"><!--?xml version="1.0" standalone="no"?-->

<svg class="SVGInline-svg" id="S_NavHome_S_22" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" x="0px" y="0px" width="22px" height="22px">
	<g id="Background">
		<path d="M 11.7168 3.1748 C 11.3276 2.7646 10.7573 2.7246 10.3477 3.1147 L 3.0073 10.1748 C 2.5977 10.5947 2.5977 11.2749 3.0176 11.6846 C 3.2173 11.875 3.4775 11.9844 3.7476 11.9844 L 5.0073 12.0254 L 5.0073 17.4844 C 5.0073 17.7852 5.2373 18.0254 5.5376 18.0254 L 9.0073 18.0254 L 9.0073 12.0254 L 13.0078 12.0254 L 13.0078 18.0254 L 16.4873 18.0254 C 16.7773 18.0254 17.0078 17.7852 17.0078 17.4941 L 17.0078 12.0254 L 18.2578 12.0254 C 18.8379 12.0547 19.3281 11.6055 19.3574 11.0249 C 19.377 10.7246 19.2578 10.4248 19.0371 10.2148 L 11.7168 3.1748 Z" fill="#707070"></path>
	</g>
	<g id="Layer%201">
	</g>
</svg></span></button></div><div class="navButton-2FYM- prevButton-zKghk"><button data-auto="prevBtn" style="outline: none;"><span role="img" class="SVGInline"><!--?xml version="1.0" standalone="no"?-->

<svg class="SVGInline-svg" id="S_NavLeft_S_22" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" x="0px" y="0px" width="22px" height="22px">
	<g id="Layer%201">
		<path d="M 7.2092 10.3975 L 12.3992 5.2178 C 12.699 4.9277 13.1692 4.9277 13.469 5.2178 C 13.759 5.5078 13.759 5.9775 13.469 6.2778 L 8.8089 10.9277 L 13.469 15.5879 C 13.759 15.8779 13.759 16.3477 13.469 16.6475 C 13.1692 16.9277 12.699 16.9277 12.3992 16.6475 L 7.219 11.4575 C 6.929 11.1577 6.929 10.6875 7.2092 10.3975 L 7.2092 10.3975 Z" fill="#707070"></path>
	</g>
</svg></span></button></div><div data-auto="screenNumbers" class="screenNumbers-_CcC_" style="min-width: 39.1125px;"><span>1 of 11</span></div><div class="navButton-2FYM- nextButton-1UXH_"><button data-auto="nextBtn" style="outline: none;"><span role="img" class="SVGInline"><!--?xml version="1.0" standalone="no"?-->

<svg class="SVGInline-svg" id="S_NavRight_S_22" viewBox="0 0 22 22" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" x="0px" y="0px" width="22px" height="22px">
	<g id="Layer%201">
		<path d="M 14.4775 10.3975 L 9.2876 5.2178 C 8.9878 4.9277 8.5176 4.9277 8.2178 5.2178 C 7.9277 5.5078 7.9277 5.9775 8.2178 6.2778 L 12.8779 10.9277 L 8.2178 15.5879 C 7.9277 15.8779 7.9277 16.3477 8.2178 16.6475 C 8.5176 16.9277 8.9878 16.9277 9.2876 16.6475 L 14.4678 11.4575 C 14.7578 11.1577 14.7578 10.6875 14.4775 10.3975 L 14.4775 10.3975 Z" fill="#707070"></path>
	</g>
</svg></span></button></div></div>
    </div>
    </div>
</template>

<style>

/* media queries */
::placeholder {
  size: 0.5px;
}
@media only screen and (max-width: 600px) {
    .col-s-12 {
      width: 100%;
      margin-top: 0;
      margin-left: 25px;
      border-left: 150px solid #fff;
      }
       .col-s-6 {
      width: 10px;
      margin-top: 0;
      margin-left: 0;
      margin-right: 0;
      }
        .comment {
      width: 50px;
      margin-top: 0;
      margin-left: 0;
      margin-right: 0;
      }
  }

/* underneath the website  starts */
.navButtons-1Qqr7 {
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
}
user agent stylesheet
div {
    display: block;
}
.prototypeAndComments-1zvNW {
    width: 100%;
    height: calc(100vh - 130px);
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
    -webkit-user-select: none;
    -ms-user-select: none;
    user-select: none;
}
body {
    font-family: "adobe-clean", sans-serif;
    margin: 0;
    padding: 0;
    height: 100%;
    overflow-y: hidden;
}

/* underneath the website ends */
.reportAbuseContainer-3neVk {
    pointer-events: auto;
}
.reportAbuse-mE4tV {
    background: #ffffff;
    padding: 8px;
    width: 16px;
    height: 16px;
}
div.buttonContainer-37nqv {
    background: #ffffff;
    border-radius: 4px;
    margin-bottom: 8px;
    outline: none;
}

.UniqueFullWidth .input-group-text {
  width: 48px;
  border-right: none;
}
.input-group-span {
  color: gray;  
  border-right: none;
}
.UniqueFullWidth [class^="fa-"], [class*=" fa-"] {
  display: inline-block;
  width: 100%;
}
.UniqueFullWidth .LoginInput {
  border-right: none;
}


.container {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
</html>