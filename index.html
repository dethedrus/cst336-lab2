<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>US Quiz</title>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/underscore.js/1.11.0/underscore-min.js" integrity="sha512-wBiNJt1JXeA/ra9F8K2jyO4Bnxr0dRPsy7JaMqSlxqTjUGHe1Z+Fm5HMjCWqkIYvp/oCbdJEivZ5pLvAtK0csQ==" crossorigin="anonymous"></script>
        <script>
            $(document).ready(function()
            /*global $*/
            /*global _*/
            /*global localStorage*/
            {
                // Global Variables
                var score = 0;
                if (localStorage.getItem("total_attempts") >= 0)
                {
                    var attempts = localStorage.getItem("total_attempts");
                }
                else
                {
                    localStorage.setItem("total_attempts", 0);
                    var attempts = localStorage.getItem("total_attempts");
                }

                // event Listeners
                $("button").on("click", gradeQuiz);
                
                // Question 5 images
                $(".q5Choice").on("click", function()
                {
                    $(".q5Choice").css("background","");
                    $(this).css("background", "rgb(255, 255, 0)");
                });

                // Question 4 choices
                displayQ4Choices();
                displayQ9Choices();

                // functions
                function displayQ4Choices()
                {
                    let q4ChoicesArray = ["Maine", "Rhode Island", "Maryland", "Delaware"];
                    q4ChoicesArray = _.shuffle(q4ChoicesArray);
                    for (let i = 0; i < q4ChoicesArray.length; i++)
                    {
                        $("#q4Choices").append(` <input type="radio" name="q4"
                        id="${q4ChoicesArray[i]}" value="${q4ChoicesArray[i]}">
                        <label for="${q4ChoicesArray[i]}"> ${q4ChoicesArray[i]}</label>`);
                    }
                }

                function displayQ9Choices()
                {
                    let q9ChoicesArray = ["New York City", "Philadelphia", "Washington DC", "Maui"];
                    q9ChoicesArray = _.shuffle(q9ChoicesArray);
                    for (let i = 0; i < q9ChoicesArray.length; i++)
                    {
                        $("#q9Choices").append(` <input type="radio" name="q9"
                        id="${q9ChoicesArray[i]}" value="${q9ChoicesArray[i]}">
                        <label for="${q9ChoicesArray[i]}"> ${q9ChoicesArray[i]}</label>`);
                    }
                }

                function isFormValid()
                {
                    let isValid = true;
                    if ($("#q1").val() == "")
                    {
                        isValid = false;
                        $("#validationFdbk").html("Question 1 is not answered");
                    }
                    return isValid;
                }
                
                function rightAnswer(index)
                {
                    $(`#q${index}Feedback`).html("Correct!");
                    $(`#q${index}Feedback`).attr("class", "bg-success text-white");
                    $(`#markImg${index}`).html("<img src='img/checkmark.png' alt='checkmark'>");
                    score += 10;
                }
                
                function wrongAnswer(index)
                {
                    $(`#q${index}Feedback`).html("Incorrect!");
                    $(`#q${index}Feedback`).attr("class", "bg-warning text-white");
                    $(`#markImg${index}`).html("<img src='img/xmark.png' alt='xmark'>");
                }
                
                function gradeQuiz()
                {
                    $("#validationFdbk").html(""); // resets validation feedback
                    if (!isFormValid())
                    {
                        return;
                    }
                    
                    // variables
                    score = 0;
                    let q1Response = $("#q1").val().toLowerCase();
                    let q2Response = $("#q2").val();
                    let q4Response = $("input[name=q4]:checked").val();
                    let q6Response = $("#q6").val();
                    let q7Response = $("input[name=q7]:checked").val();
                    let q9Response = $("input[name=q9]:checked").val();
                    let q10Response = $("input[name=q10]:checked").val();
                    
                    // Question 1
                    if (q1Response == "sacramento")
                    {
                        rightAnswer(1);
                    }
                    else
                    {
                        wrongAnswer(1);
                    }
                    
                    // Question 2
                    if (q2Response == "mo")
                    {
                        rightAnswer(2);
                    }
                    else
                    {
                        wrongAnswer(2);
                    }
                    
                    // Question 3
                    if ($("#Jefferson").is(":checked") && $("#Roosevelt").is(":checked") && !$("#Jackson").is(":checked") && !$("#Franklin").is(":checked"))
                    {
                        rightAnswer(3);
                    }
                    else
                    {
                        wrongAnswer(3);
                    }

                    // Question 4
                    if(q4Response == "Rhode Island")
                    {
                        rightAnswer(4);
                    }
                    else
                    {
                        wrongAnswer(4);
                    }
                    
                    // Question 5
                    if ($("#seal2").css("background-color") == "rgb(255, 255, 0)")
                    {
                        rightAnswer(5);
                    }
                    else
                    {
                        wrongAnswer(5);
                    }
                    
                    // Question 6
                    if (q6Response == "50")
                    {
                        rightAnswer(6);
                    }
                    else
                    {
                        wrongAnswer(6);
                    }
                    
                    // Question 7
                    if (q7Response == "False")
                    {
                        rightAnswer(7);
                    }
                    else
                    {
                        wrongAnswer(7);
                    }
                    
                    // Question 8
                    if ($("#Guam").is(":checked") && $("#USVI").is(":checked") && !$("#Canada").is(":checked") && !$("#Trinidad").is(":checked"))
                    {
                        rightAnswer(8);
                    }
                    else
                    {
                        wrongAnswer(8);
                    }
                    
                    // Question 9
                    if (q9Response == "New York City")
                    {
                        rightAnswer(9);
                    }
                    else
                    {
                        wrongAnswer(9);
                    }
                    
                    // Question 10
                    if (q10Response == "True")
                    {
                        rightAnswer(10);
                    }
                    else
                    {
                        wrongAnswer(10);
                    }
                    
                    // Scoring and optional victory message
                    if (score > 79)
                    {
                        $("#totalScore").html(`Total Score: ${score}`).css("color", "RGB(0, 255, 0)");
                        $("#passingGrade").html(`<b>Congratulations on your mastery<p>of basic US geography!</b>`);
                    }
                    else
                    {
                        $("#totalScore").html(`Total Score: ${score}`).css("color", "RGB(255, 0, 0)");
                        $("#passingGrade").html(`<b>Better study your US civics!</b>`);
                    }

                    // Attempt tracker called from localStorage
                    $("#totalAttempts").html(`<em>Total Attempts: ${++attempts}</em>`);
                    localStorage.setItem("total_attempts", attempts);
                }
            }); // ready
        </script>
    </head>

    <body class="text-center">
        <h1 class="jumbotron">US Geography Quiz</h1>
        <h3><span id="markImg1"></span>What is the capitol of California?</h3>
        <input type="text" id="q1">
        <br><br>
        <div id="q1Feedback"></div>
        <br>
        
        <h3><span id="markImg2"></span>What is the longest river?</h3>
        <select id="q2">
            <option value="">Select one:</option>
            <option value="ms">Mississippi</option>
            <option value="mo">Missouri</option>
            <option value="co">Colorado</option>
            <option value="de">Delaware</option>
        </select>
        <br><br>
        <div id="q2Feedback"></div>
        <br>
        
        <h3><span id = "markImg3"></span>What presidents are carved into Mount Rushmore?</h3>
        <input type = "checkbox" id="Jackson"><label for="Jackson">Andrew Jackson</label>
        <input type = "checkbox" id="Franklin"><label for="Franklin">Benjamin Franklin</label>
        <input type = "checkbox" id="Jefferson"><label for="Jefferson">Thomas Jefferson</label>
        <input type = "checkbox" id="Roosevelt"><label for="Roosevelt">Theodore Roosevelt</label>
        <br><br>
        <div id = "q3Feedback"></div>
        <br>
        
        <h3><span id = "markImg4"></span>What is the smallest US state?</h3>
        <div id = "q4Choices"></div>
        <div id = "q4Feedback"></div>
        <br></br>
        
        <h3><span id = "markImg5"></span>What image is the Great Seal of the State of California?</h3>
        <img src="img/seal1.png" alt="Seal 1" class="q5Choice" id="seal1">
        <img src="img/seal2.png" alt="Seal 2" class="q5Choice" id="seal2">
        <img src="img/seal3.png" alt="Seal 3" class="q5Choice" id="seal3">
        <div id = "q5Feedback"></div>
        <br></br>
        
        <h3><span id = "markImg6"></span>How many states are in the US?</h3>
        <input type="text" id="q6">
        <br><br>
        <div id="q6Feedback"></div>
        <br></br>
        
        <h3><span id = "markImg7"></span>Hawaii became a state in 1949</h3>
        <input type = "radio" name = "q7" value = "True">True
        <input type = "radio" name = "q7" value = "False">False
        <br></br>
        <div id = "q7Feedback"></div>
        <br></br>
        
        <h3><span id = "markImg8"></span>Which of the following are US protectorates?</h3>
        <input type = "checkbox" id="USVI"><label for="USVI">US Virgin Islands</label>
        <input type = "checkbox" id="Trinidad"><label for="Trinidad">Trinidad</label>
        <input type = "checkbox" id="Guam"><label for="Guam">Guam</label>
        <input type = "checkbox" id="Canada"><label for="Canada">Canada</label>
        <br></br>
        <div id = "q8Feedback"></div>
        <br></br>
        
        <h3><span id = "markImg9"></span>Which city was the original US capital?</h3>
        <div id = "q9Choices"></div>
        <div id = "q9Feedback"></div>
        <br></br>
        
        <h3><span id = "markImg10"></span>Washington DC couldn't vote in federal elections until 1964</h3>
        <input type = "radio" name = "q10" value = "True">True
        <input type = "radio" name = "q10" value = "False">False
        <br></br>
        <div id = "q10Feedback"></div>
        <br></br>

        <h3 id="validationFdbk" class="bg-danger text-white"></h3>
        <button class="btn btn-primary">Submit Quiz</button>
        <br><br>
        <h2 id = "totalScore"></h2>
        <h2 id = "passingGrade"></h2>
        
        <h5 id = "totalAttempts"></h5>
    </body>
</html>