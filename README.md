<!DOCTYPE html>
<head>
    <title>Shruti's Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <style>
        body{
            background-color: azure;
        }
        .container{
            display: grid;
            grid-template-rows: 1fr 1fr 1fr;
            height: 100vh;
            background-color: azure;
            

        }
        .banner{
            display: grid;;
            background-color: aquamarine;

            

        }
            
            
        
        
        .head{
            display: grid;
            /* background-color: azure; */
            
            
            
        }
        .pfp{
            display: grid;
            justify-content: center;
            align-items: center;
            
        }
        img{
            border-radius: 50%;
        }
        h3{
            display: grid;
            justify-content: center;
            
            color: darkgreen;
           
        }
        .aboutme{
            margin: 0 auto; /* Added */
        float: none; /* Added */
        margin-bottom: 10px; /* Added */
            
        }
        
        

        
        

        
        
        
        
        
        

    </style>
</head>
<body>
    <div class="container">
        <div class="banner">
            <p>
            </p>
            <p></p>
            <p></p>
            <p></p>
            
        <div class="head">
                <div class="container">
                    <header class="d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-3 mb-4 border-bottom">
                      <div class="col-md-3 mb-2 mb-md-0">
                        <a href="/" class="d-inline-flex link-body-emphasis text-decoration-none">
                          <svg class="bi" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
                        </a>
                      </div>
                
                      <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
                        <li><a href="#aboutme" class="nav-link px-2">About Me</a></li>
                        <li><a href="#" class="nav-link px-2">Skills</a></li>
                        <li><a href="#" class="nav-link px-2">Education</a></li>
                        <li><a href="#" class="nav-link px-2">Projects</a></li>
                        <li><a href="#" class="nav-link px-2">Co-Curricular</a></li>
                      </ul>
                
                      <div class="col-md-3 text-end">
                        
                        <button type="button" class="btn btn-success">contact me</button>
                      </div>
                    </header>
                    <div class="pfp">
                        <img src="shruti.jpg" alt="shrutipfp" height="200px" >
                      </div>
                    <h3> hi!</h3>
                    
                    
                  </div>
                  
        </div>


        </div>
        <div class="about" id="aboutme">
            <div class="aboutme" style="width: 18rem;">
                <div class="card-body">
                  <h5 class="card-title" style="text-align: center;">Greetings!</h5>
                  <h6 class="card-subtitle mb-2 text-body-secondary" style="text-align: center;">Brief About Me</h6>
                  <!-- <p class="card-text"></p> -->
                  <hr>
                  
                </div>
              </div>
            <div class="row g-4 py-5 row-cols-1 row-cols-lg-3">
                <div class="feature col">
                  <div class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2 mb-3">
                    <svg class="bi" width="1em" height="1em"><use xlink:href="profile.png"></use></svg>
                  </div>
                  <h3 class="fs-2 text-body-emphasis">Profile</h3>
                  <p style="text-align:justify ;">An Eager and on-going graduate with a degree in Computer Science and a wide keen
                    brain for software development.
                    Good command and Proficient in Java and Python, with a strong foundation in
                    algorithm and website design.
                    Effective communicator with an ability to convey complex technical concepts to
                    both technical and non-technical audiences.
                    Longing to contribute to and learn from a software developing team and apply
                    problem-solving skills in a collaborative and technical environment.</p>
                  
                    
                </div>
                <div class="feature col">
                  <div class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2 mb-3">
                    <svg class="bi" width="1em" height="1em"><use xlink:href="#people-circle"></use></svg>
                  </div>
                  <h3 class="fs-2 text-body-emphasis">Featured title</h3>
                  <p>Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
                  <a href="#" class="icon-link">
                    Call to action
                    <svg class="bi"><use xlink:href="#chevron-right"></use></svg>
                  </a>
                </div>
                <div class="feature col">
                  <div class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2 mb-3">
                    <svg class="bi" width="1em" height="1em"><use xlink:href="#toggles2"></use></svg>
                  </div>
                  <h3 class="fs-2 text-body-emphasis">Featured title</h3>
                  <p>Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
                  <a href="#" class="icon-link">
                    Call to action
                    <svg class="bi"><use xlink:href="#chevron-right"></use></svg>
                  </a>
                </div>
              </div>
            
            
              

    </div>
    
        
    

    
    
    

</body>
