<!--In this page, assume that the instructor on his courses page, and he clicks on "Make Quiz" button -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <!-- for internet explorer compatibality-->
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!--first mobile meta-->
  <link rel="stylesheet" type="text/css" href="../../layout/css/bootstrap.css">
  	 <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
    <script type="text/javascript" src="../../layout/js/jquery-3.1.1.min.js"></script>
	<script type="text/javascript" src="../../layout/js/bootstrap.min.js"></script>


	<link rel="stylesheet" type="text/css" href="../../layout/css/make quiz_styleSheet.css">
	<link href="https://fonts.googleapis.com/css?family=Josefin+Sans" rel="stylesheet">
	<title>Make Quiz</title>
	</head>
	<body style="background-color: #e6f3ff;">
		<div class="container makeQuiz_container" style="padding-top: 20px; background-color: #fff; margin: 90px 70px; border-radius: 10px;padding-bottom: 50px;">
		<br><br><br>
			<p class="Num_p" style="font-size: 20px; display: inline; padding-right: 30px; margin-left: 80px; padding-top: : 15px;">Number of "MCQ" questions: </p>
			<select id="mcqNum" style="width: 70px; height: 30px;">
			<?php
				for ($i=0; $i <= 200; $i++) { 
					echo "<option>" . $i . "</option>";
				}
			?>
			</select>
			<p class="Num_p" style="font-size: 20px; display: inline; padding-left: 100px; padding-right: 30px;">Number of problems: </p>
			<select style="width: 70px; height: 30px;">
			<?php
				for ($i=0; $i <= 200; $i++) { 
					echo "<option>" . $i . "</option>";
				}
			?>
			</select>
			<button type="button" class="btn btn-default start_button" style="margin-left: 120px; width: 75px;">Start!</button>
				<br><br><hr><br><br>
				<?php
				$mcqCount= 10;
					for ($i=0; $i < $mcqCount ; $i++) { 
						echo '<div class="mcqQuestion" style="border: solid 1px #337ab7; border-radius: 15px; margin: 20px; padding: 10px; display: none;">
							<br>
							<h4>Question title:</h4>
							<form method="" action="">
								<textarea name="questionTitle" style="width: 1050px; height: 50px; columns: 5; resize: none;"></textarea>
								<br><br>
								<h4>Answers:</h4>
								<span>A:</span> <input type="text" name="answerA" style="width: 300px; height: 25px;">
								<span style="margin-left: 50px;">B:</span> <input type="text" name="answerB" style="width: 300px; height: 25px;">
								<span style="margin-left: 50px;">C:</span> <input type="text" name="answerC" style="width: 300px; height: 25px;">
								<br><br>
								<span>D:</span> <input type="text" name="answerD" style="width: 300px; height: 25px;">
								<span style="margin-left: 50px;">E:</span> <input type="text" name="answerE" style="width: 300px; height: 25px;">
								 <!-- E is not required -->
								<br><br><br>
								<h4 style="display: inline; margin-right: 20px;">Correct answer:</h4>
								<select style="width: 80px; height:30px;">
									<option>A</option>
									<option>B</option>
									<option>C</option>
									<option>D</option>
									<option>E</option>
								</select>
								<h4 style="display: inline; margin-left: 80px; margin-right: 20px;">Question Grade: </h4>
								<select style="width: 80px; height:30px;">
									<option>1</option>
									<option>2</option>
									<option>3</option>
									<option>4</option>
									<option>5</option>
								</select>
							</form>
						</div>';
					}
				?>
				<br><br>

						<div class="problemQuestion" style="border: solid 1px #337ab7; border-radius: 15px;
								 margin: 20px; padding: 10px; display: none;">
								<form action="" method="">
								<h4 style="display: inline;">Problem name: </h4>
								<input type="text" name="problem_name" style="width: 600px; margin-left: 50px;">
								<h4>Problem content:</h4>
								<textarea name="problem_content" style="width: 1000px; height: 300px; resize: none;"></textarea>
								<h4>Test cases:</h4>
								<div class="testCases">
									<div style="display: inline-block; margin-right: 100px;">
										<h5>Inputs:</h5>
										<textarea name="input_test_case" style="width: 400px; height: 100px; resize: none; display: inline;"></textarea>
									</div>
									<div style="display: inline-block;">
										<h5>Outputs:</h5>
										<textarea name="output_test_case" style="width: 400px; height: 100px; resize: none; display: inherit;"></textarea>
									</div>
									<br><br>
									<!--
										<p style="display: inline; margin-right: 40px;">Another test case?</p>
										<button type="button" class="btn btn-primary add_test_case_btn">Add test case</button>
									-->
								</div>
								<br><br>
								<!--
									<div class="another_testCases" style="display: none;">
										<div style="display: inline-block; margin-right: 100px;">
											<h5>Input:</h5>
											<textarea name="input_test_case" style="width: 400px; height: 100px; resize: none; display: inline;"></textarea>
										</div>
										<div style="display: inline-block;">
											<h5>Output:</h5>
											<textarea name="output_test_case" style="width: 400px; height: 100px; resize: none; display: inherit;"></textarea>
										</div>
									
									<br><br>
									<p style="display: inline; margin-right: 40px;">Another test case?</p>
									<button type="button" class="btn btn-primary add_test_case_btn">Add test case</button>
									</div>
								-->
								<br><br>
							</form>
						</div>
				
				<center><button type="button" class="btn btn-danger submit_quiz_btn" style="width: 400px; display: none;">Submit Quiz!</button></center>
		</div>

		<script type="text/javascript" src="../../layout/js/jquery-3.1.1.min.js"></script>
		<script type="text/javascript" src="../../layout/js/make quiz.js"></script>
	</body>
	</html>
