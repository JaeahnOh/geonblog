---
layout: post-index
permalink: /lecture_2/
title: 기본 자료형
description: "기본 자료형 사용법과 예제"
---


<!DOCTYPE html>
<html class=' composer' dir='ltr' lang='en' xmlns:fb='https://www.facebook.com/2008/fbml' xmlns:og='http://ogp.me/ns#' xmlns='http://www.w3.org/1999/xhtml'>
<head>
<script>

  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-25136408-1', 'codecademy.com');
  ga('send', 'pageview');

  // Sets a ga-custom-dimension on the "hit"
  // - This usage: Indicates that the view was using the non-rebrand (old world)
  ga('set', 'eng:deprecated', "old-ui");

  // chartbeat
  var _sf_startpt=(new Date()).getTime();

// Generic
var root_url = "http://www.codecademy.com/";

// CCDATA
window.CCDATA = {};
CCDATA.env = 'production';
CCDATA.request_host = 'www.codecademy.com';

CCDATA.secureSandboxIndexPath = 'http://cdn-production.codecademy.com/assets/secure/index-c5bf1319f62cb07c26239e761a9ed5c9.html';

CCDATA.asset_host = 'cdn-production.codecademy.com';
CCDATA.assets_compiled = true;

CCDATA.available_locales = 'en|ko|fa|ru|es-AR|ja|fr|zh|fr-FR|pt-BR|de|ky-KG|es|pt|ar';

CCDATA.API_HOST = '/api';

  CCDATA.current_user = {"_id":"54510d5f80ff3310580002c5","created_at":"2014-10-29T11%3A53%3A03-04%3A00","url":"http%3A%2F%2Fwww.codecademy.com%2Fusers%2Fwanpyo","username":"wanpyo","handle":"wanpyo","email":"abcdfo506%40naver.com","name":"","profile_image_url":"http%3A%2F%2Fwww.gravatar.com%2Favatar%2Fbdfe58b3b6965816e1a16470a98cc71a%3Fs%3D140%26d%3Dretro","points":0,"total_points":0,"roles":[],"enabled_experiments":[],"deleted":false};
  CCDATA.current_user.authentication_token = "44RrfMJYcvGUw5yZYoy7"



</script>


<title>Python Syntax | Codecademy</title>
<meta charset='utf-8'>
<meta content='IE=edge,chrome=1' http='{:equiv=&gt;"X-UA-Compatible"}'>
<meta content="Codecademy is the easiest way to learn how to code. It's interactive, fun, and you can do it with your friends." name='description'>
<link href='/favicon.ico' rel='shortcut icon'>
<link href='/blog.rss' rel='alternate' title='Codecademy Blog' type='application/rss+xml'>
<meta content='width=device-width, initial-scale=1.0, user-scalable=no' name='viewport'>



<meta property="fb:app_id" content="212500508799908"/>
<meta property="og:url" content="http://www.codecademy.com/courses/introduction-to-python-6WeG3/0/1?curriculum_id=4f89dab3d788890003000096"/>
<meta property="og:site_name" content="Codecademy"/>

  <meta property="og:type" content="article"/>
  <meta property="og:title" content="Python Syntax"/>
  <meta property="og:description" content="Codecademy is the easiest way to learn how to code. It&#x27;s interactive, fun, and you can do it with your friends."/>


<meta content="authenticity_token" name="csrf-param" />
<meta content="A7C8RXnQs93rCz/IUw4qCFrV08Lm/DRwSii/18epq7I=" name="csrf-token" />

  <link href="http://cdn-production.codecademy.com/assets/application-ltr-4773cb2fd527655d4c7db84e17ce1b67.css" media="screen" rel="stylesheet" type="text/css" />

<link href="http://fonts.googleapis.com/css?family=Open+Sans:100,400,700" media="screen" rel="stylesheet" type="text/css" />
<link href="http://cdn-production.codecademy.com/assets/rebrand/layouts/patch-db27df937e1166ce5a799048d8d7a137.css" media="screen" rel="stylesheet" type="text/css" />

<!--[if gte IE 9]>
<style type="text/css">
  .gradient {filter: none;}
</style>
<![endif]-->

<script src="http://cdn-production.codecademy.com/assets/templates/widgets-en-81534a78963be1efb02824cb3b86c135.js" type="text/javascript"></script>
</head>
<body class='projects show signed_in composer'>
  <script>
  CCDATA.codexHosts = ["http://54.243.202.158:80","http://54.243.202.158:443"];
  CCDATA.codexCredentials = ["1414598007","introduction-to-python-6WeG3.wanpyo","03712ad87ab9e2601083db7448d68032f88a92a6"];
  </script>


<script src="http://cdn-production.codecademy.com/assets/templates/composer-en-c65dd524db77b8b51b0478343b33b977.js" type="text/javascript"></script>


<input type="hidden" id="data-source" value="conserv"/>

<script>
  CCDATA.composer = {};
  CCDATA.composer.experiments = {};
  CCDATA.composer.lastHint = {};
  CCDATA.composer.backtestType = 'cached_invalid_answers';
  CCDATA.composer.course = {"_id":"4fcba68767e7c1000304119b","name":"Python Syntax","projects":[{"id":"4fcbf771153c8a0003022c6a","checkpoints":[{"_id":"4fcbf772c120ab00030236fd","index":0,"code_reset":true,"default_files":[{"filename":"script.py","content":"print \"Welcome to Python!\""}],"entry":"Python is an easy to learn programming language. You can use it to create web apps, games, even a search engine!\n\nReady to learn Python? Click Save \u0026 Submit Code to continue!","entry_html":"\u003Cp\u003EPython is an easy to learn programming language. You can use it to create web apps, games, even a search engine!\u003C/p\u003E\n\n\u003Cp\u003EReady to learn Python? Click Save \u0026amp; Submit Code to continue!\u003C/p\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"If the loading bar fills but doesn't fade away, try refreshing the page.","hint_html":"\u003Cp\u003EIf the loading bar fills but doesn\u0026#39;t fade away, try refreshing the page.\u003C/p\u003E\n","instruction":"Ready to learn Python? Click Save \u0026 Submit Code to continue!","instruction_html":"\u003Cp\u003EReady to learn Python? Click Save \u0026amp; Submit Code to continue!\u003C/p\u003E\n","name":"Welcome!","test_functions":"return True\n","preview_button":false,"is_current_checkpoint":true},{"_id":"4fd2aa84e17f5c000300562b","index":1,"code_reset":true,"default_files":[{"filename":"script.py","content":"# Write your code below!\n"}],"entry":"Creating web apps, games, and search engines all involve storing and working with different types of data. They do so using **variables**. A **variable** stores a piece of data, and gives it a specific name.\n\nFor example:\n\n```\nspam = 5\n```\n\nThe variable `spam` now stores the number `5`.","entry_html":"\u003Cp\u003ECreating web apps, games, and search engines all involve storing and working with different types of data. They do so using \u003Cstrong\u003Evariables\u003C/strong\u003E. A \u003Cstrong\u003Evariable\u003C/strong\u003E stores a piece of data, and gives it a specific name.\u003C/p\u003E\n\n\u003Cp\u003EFor example:\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode\u003Espam = 5\n\u003C/code\u003E\u003C/pre\u003E\n\n\u003Cp\u003EThe variable \u003Ccode\u003Espam\u003C/code\u003E now stores the number \u003Ccode\u003E5\u003C/code\u003E.\u003C/p\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"Make sure to put `my_variable` on the left side of the `=`, and `10` on the right.\n\nYou will notice that the window says \"None\" in it when you run the code. This is the \"result\" of your code, but you can generally ignore it.","hint_html":"\u003Cp\u003EMake sure to put \u003Ccode\u003Emy_variable\u003C/code\u003E on the left side of the \u003Ccode\u003E=\u003C/code\u003E, and \u003Ccode\u003E10\u003C/code\u003E on the right.\u003C/p\u003E\n\n\u003Cp\u003EYou will notice that the window says \u0026quot;None\u0026quot; in it when you run the code. This is the \u0026quot;result\u0026quot; of your code, but you can generally ignore it.\u003C/p\u003E\n","instruction":"1. Set the variable `my_variable` equal to the value `10`.\n2. Click the Save \u0026 Submit button to run your code.","instruction_html":"\u003Col\u003E\n\u003Cli\u003ESet the variable \u003Ccode\u003Emy_variable\u003C/code\u003E equal to the value \u003Ccode\u003E10\u003C/code\u003E.\u003C/li\u003E\n\u003Cli\u003EClick the Save \u0026amp; Submit button to run your code.\u003C/li\u003E\n\u003C/ol\u003E\n","name":"Variables","test_functions":"try:\n\tmy_variable\nexcept NameError:\n\treturn \"Did you remember to create a variable called my_variable?\"\n\nif error:\n\treturn \"Your code looks a bit off. Check the Hint if you need help! Here's the error message: \" + str(error)\n\nif my_variable != 10:\n\treturn \"The variable should contain the value 10.\"\n\t\nreturn True\n","preview_button":false,"is_current_checkpoint":false},{"_id":"4fd2acfdb5b9fe000300601e","index":2,"code_reset":true,"default_files":[{"filename":"script.py","content":"# Set the variables to the values listed in the instructions!\n\n"}],"entry":"Great! You just stored a number in a variable. Numbers are one data type we use in programming. A second data type is called a **boolean**. \n\nA **boolean** is like a light switch. It can only have two values. Just like a light switch can only be on or off, a boolean can only be `True` or `False`.\n\nYou can use variables to store booleans like this:\n\n```\na = True\nb = False\n```","entry_html":"\u003Cp\u003EGreat! You just stored a number in a variable. Numbers are one data type we use in programming. A second data type is called a \u003Cstrong\u003Eboolean\u003C/strong\u003E. \u003C/p\u003E\n\n\u003Cp\u003EA \u003Cstrong\u003Eboolean\u003C/strong\u003E is like a light switch. It can only have two values. Just like a light switch can only be on or off, a boolean can only be \u003Ccode\u003ETrue\u003C/code\u003E or \u003Ccode\u003EFalse\u003C/code\u003E.\u003C/p\u003E\n\n\u003Cp\u003EYou can use variables to store booleans like this:\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode\u003Ea = True\nb = False\n\u003C/code\u003E\u003C/pre\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"Remember to capitalize `True`!","hint_html":"\u003Cp\u003ERemember to capitalize \u003Ccode\u003ETrue\u003C/code\u003E!\u003C/p\u003E\n","instruction":"Set the following variables to the corresponding values:\n\n1. `my_int` to the value `7`\n2. `my_float` to the value `1.23`\n3. `my_bool` to the value `True`","instruction_html":"\u003Cp\u003ESet the following variables to the corresponding values:\u003C/p\u003E\n\n\u003Col\u003E\n\u003Cli\u003E\u003Ccode\u003Emy_int\u003C/code\u003E to the value \u003Ccode\u003E7\u003C/code\u003E\u003C/li\u003E\n\u003Cli\u003E\u003Ccode\u003Emy_float\u003C/code\u003E to the value \u003Ccode\u003E1.23\u003C/code\u003E\u003C/li\u003E\n\u003Cli\u003E\u003Ccode\u003Emy_bool\u003C/code\u003E to the value \u003Ccode\u003ETrue\u003C/code\u003E\u003C/li\u003E\n\u003C/ol\u003E\n","name":"Booleans","test_functions":"try:\n\tmy_int\nexcept NameError:\n\treturn \"Did you define a variable called my_int?\"\n\ntry:\n\tmy_float\nexcept NameError:\n\treturn \"Did you define a variable called my_float?\"\n\ntry:\n\tmy_bool\nexcept NameError:\n\treturn \"Did you define a variable called my_bool?\"\n\nif my_int != 7:\n\treturn \"The variable my_int should have the value 7.\"\n\nif my_float != 1.23:\n\treturn \"The variable my_float should have the value 1.23.\"\n\t\nif my_bool != True:\n\treturn \"The variable my_bool should have the value True.\"\n\n\"\"\" Cant print from SCT in current setup\nprint \"Python detected the following datatypes:\"\nprint \"my_int is of\", type(my_int)\nprint \"my_float is of\", type(my_float)\nprint \"my_bool is of\", type(my_bool)\n\"\"\"\n\nif error: \n    return \"Something in your code isn't right! Reread the instructions and check the hint for some help. Here's the error message: \" + str(error)\nreturn True\n","preview_button":false,"is_current_checkpoint":false},{"_id":"4fd2aff3b5b9fe000300684b","index":3,"code_reset":true,"default_files":[{"filename":"script.py","content":"# my_int is set to 7 below. What do you think\n# will happen if we reset it to 3 and print the result?\n\nmy_int = 7\n\n# Change the value of my_int to 3 on line 8!\n\nmy_int =\n\n# Here's some code that will print my_int to the console:\n# The print keyword will be covered in detail soon!\n\nprint my_int"}],"entry":"Now you know how to use variables to store values.\n\nSay `my_int = 7`. You can change the value of a variable by \"reassigning\" it, like this:\n\n```\nmy_int = 3\n```","entry_html":"\u003Cp\u003ENow you know how to use variables to store values.\u003C/p\u003E\n\n\u003Cp\u003ESay \u003Ccode\u003Emy_int = 7\u003C/code\u003E. You can change the value of a variable by \u0026quot;reassigning\u0026quot; it, like this:\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode\u003Emy_int = 3\n\u003C/code\u003E\u003C/pre\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"All you need to do is type `3` after the equals sign on line 8.","hint_html":"\u003Cp\u003EAll you need to do is type \u003Ccode\u003E3\u003C/code\u003E after the equals sign on \u003Ca href=\"javascript:void(0)\" class=\"line-no\" data-from=\"8\" data-to=\"\"\u003Eline 8\u003C/a\u003E.\u003C/p\u003E\n","instruction":"Try it and see! Change the value of `my_int` from `7` to `3` in the editor","instruction_html":"\u003Cp\u003ETry it and see! Change the value of \u003Ccode\u003Emy_int\u003C/code\u003E from \u003Ccode\u003E7\u003C/code\u003E to \u003Ccode\u003E3\u003C/code\u003E in the editor\u003C/p\u003E\n","name":"You've Been Reassigned","test_functions":"if error:\n\treturn \"Did you remember to complete the code on line 8? Your code threw the following error: \" + str(error)\n\t\ntry:\n    if my_int != 3:\n    \treturn \"It looks like my_int is %s instead of 3.\" % str(my_int)\nexcept NameError as ne:\n    return \"Make sure that my_int is properly defined! Your code threw the following NameError: \" + str(ne)\nexcept Exception as e:\n    return \"Your code seems to have the following error: \" + str(e)\n    \nreturn True\n","preview_button":false,"is_current_checkpoint":false}],"description":"Python was developed to be clear, powerful, and fun to use. We'll start with a quick note on what Python is and how it's used, then we'll jump right into writing code! This course assumes no prior knowledge in Python.","name":"Variables and Data Types","checkpoints_count":4,"completed_checkpoints_count":0,"is_current_project":true,"index":0,"completed":false,"author":{"_id":"4f04f1847057120003006c12","handle":"Eric Weinstein","profile_image_url":"https://codecademy-production.s3.amazonaws.com/profile_thumbnail/50b7d7b3cf6c0f9b11000087_795211733.jpg?AWSAccessKeyId=AKIAI7LDEVVIL32I5WXQ\u0026Expires=1414601607\u0026Signature=bDzdMOBQcYm2P6D4vJ2R6EaXAGc%3D","self_url":"/v1/users/4f04f1847057120003006c12"},"continue_to_section":{"name":"Whitespace and Statements","url":"http://www.codecademy.com/courses/introduction-to-python-6WeG3/1?curriculum_id=4f89dab3d788890003000096"}},{"id":"4fcba68767e7c1000304119c","checkpoints":[{"_id":"4fcd6741b84bbb0003024e1b","index":0,"code_reset":true,"default_files":[{"filename":"script.py","content":"def spam():\neggs = 12\nreturn eggs\n        \nprint spam()"}],"entry":"In Python, whitespace is used to structure code. Whitespace is important, so you have to be careful with how you use it.","entry_html":"\u003Cp\u003EIn Python, whitespace is used to structure code. Whitespace is important, so you have to be careful with how you use it.\u003C/p\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":null,"hint_html":null,"instruction":"The code on the right is badly formatted. Hit \"Save \u0026 Submit Code\" to see what happens.\n\nYou should see an error message. We'll fix it in the next exercise!","instruction_html":"\u003Cp\u003EThe code on the right is badly formatted. Hit \u0026quot;Save \u0026amp; Submit Code\u0026quot; to see what happens.\u003C/p\u003E\n\n\u003Cp\u003EYou should see an error message. We\u0026#39;ll fix it in the next exercise!\u003C/p\u003E\n","name":"Whitespace","test_functions":"if type(error) == IndentationError:\n\tprint \"This code is badly formatted on purpose! Go on to the next exercise to see correct formatting.\"\nreturn True\n","preview_button":false,"is_current_checkpoint":false},{"_id":"4fd2b467e17f5c0003006fc8","index":1,"code_reset":true,"default_files":[{"filename":"script.py","content":"def spam():\neggs = 12\nreturn eggs\n        \nprint spam()"}],"entry":"Now let's examine the error from the last lesson:\n\n```\nIndentationError: expected an indented block\n```\n\nYou'll get this error whenever your whitespace is off. ","entry_html":"\u003Cp\u003ENow let\u0026#39;s examine the error from the last lesson:\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode\u003EIndentationError: expected an indented block\n\u003C/code\u003E\u003C/pre\u003E\n\n\u003Cp\u003EYou\u0026#39;ll get this error whenever your whitespace is off. \u003C/p\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"Your code should look something like this:\n\n```python\ndef spam():\n    eggs = 12\n    return eggs\n\nprint spam()\n```","hint_html":"\u003Cp\u003EYour code should look something like this:\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode class=\"python\"\u003Edef spam():\n    eggs = 12\n    return eggs\n\nprint spam()\n\u003C/code\u003E\u003C/pre\u003E\n","instruction":"Properly indent the code with four spaces before eggs on line 2 and another four before return on line 3.\n\nYou should indent your code with four spaces.","instruction_html":"\u003Cp\u003EProperly indent the code with four spaces before eggs on \u003Ca href=\"javascript:void(0)\" class=\"line-no\" data-from=\"2\" data-to=\"\"\u003Eline 2\u003C/a\u003E and another four before return on \u003Ca href=\"javascript:void(0)\" class=\"line-no\" data-from=\"3\" data-to=\"\"\u003Eline 3\u003C/a\u003E.\u003C/p\u003E\n\n\u003Cp\u003EYou should indent your code with four spaces.\u003C/p\u003E\n","name":"Whitespace Means Right Space","test_functions":"if error:\n\treturn \"Check your indentation and make sure your code is correct. Check the hint if you need help. Your code threw the following error: \" + str(error)\n\nif spam() != 12:\n\treturn \"Did you indent lines 2 and 3 with four spaces?\"\nif len(CC.prints()) \u003C 1:\n\treturn \"It looks like you didn't print anything! Make sure not to indent the print statement!\"\nreturn True\n","preview_button":false,"is_current_checkpoint":false},{"_id":"4fd2b5c672cf5000030074fd","index":2,"code_reset":true,"default_files":[{"filename":"script.py","content":""}],"entry":"The window in the top right corner of the page is called the interpreter. The interpreter runs your code line by line, and checks for any errors.\n\n```python\ncats = 3\n```\n\nIn the above example, we create a variable `cats` and assign it the value of `3`.","entry_html":"\u003Cp\u003EThe window in the top right corner of the page is called the interpreter. The interpreter runs your code line by line, and checks for any errors.\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode class=\"python\"\u003Ecats = 3\n\u003C/code\u003E\u003C/pre\u003E\n\n\u003Cp\u003EIn the above example, we create a variable \u003Ccode\u003Ecats\u003C/code\u003E and assign it the value of \u003Ccode\u003E3\u003C/code\u003E.\u003C/p\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"Remember, you assign values with the `=` sign, like so:\n\n```python\nexample_variable = True\n```","hint_html":"\u003Cp\u003ERemember, you assign values with the \u003Ccode\u003E=\u003C/code\u003E sign, like so:\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode class=\"python\"\u003Eexample_variable = True\n\u003C/code\u003E\u003C/pre\u003E\n","instruction":"1. Create a variable called `spam` and assign it the value of `True`.\n2. Create a variable called `eggs` and assign it the value of `False`.","instruction_html":"\u003Col\u003E\n\u003Cli\u003ECreate a variable called \u003Ccode\u003Espam\u003C/code\u003E and assign it the value of \u003Ccode\u003ETrue\u003C/code\u003E.\u003C/li\u003E\n\u003Cli\u003ECreate a variable called \u003Ccode\u003Eeggs\u003C/code\u003E and assign it the value of \u003Ccode\u003EFalse\u003C/code\u003E.\u003C/li\u003E\n\u003C/ol\u003E\n","name":"A Matter of Interpretation","test_functions":"try:\n\tspam\nexcept NameError:\n\treturn \"Did you define a variable called spam?\"\n\ntry:\n\teggs\nexcept NameError:\n\treturn \"Did you define a variable called eggs?\"\n\nif error:\n\treturn \" You have an error in your code! Look for variable name typos or improper use of the = operator. And check the error message for more details: \" + str(error)\n\t\nif not (spam is True):\n\treturn \"The variable spam should have the value True!\"\nif not (eggs is False):\n\treturn \"The variable eggs should have the value False!\"\n\nreturn True\n","preview_button":false,"is_current_checkpoint":false}],"description":"Now that you're getting the hang of variables, values, and assignment (think of them like the subjects, objects, and verbs of English sentences), let's take a look at whitespace and statements: the sentences of our new Python language.","name":"Whitespace and Statements","checkpoints_count":3,"completed_checkpoints_count":0,"is_current_project":false,"index":1,"completed":false,"author":{"_id":"4f04f1847057120003006c12","handle":"Eric Weinstein","profile_image_url":"https://codecademy-production.s3.amazonaws.com/profile_thumbnail/50b7d7b3cf6c0f9b11000087_795211733.jpg?AWSAccessKeyId=AKIAI7LDEVVIL32I5WXQ\u0026Expires=1414601607\u0026Signature=bDzdMOBQcYm2P6D4vJ2R6EaXAGc%3D","self_url":"/v1/users/4f04f1847057120003006c12"},"continue_to_section":{"name":"Comments","url":"http://www.codecademy.com/courses/introduction-to-python-6WeG3/2?curriculum_id=4f89dab3d788890003000096"}},{"id":"4fd01880459159000302d648","checkpoints":[{"_id":"4fd01881891c87000302de05","index":0,"code_reset":true,"default_files":[{"filename":"script.py","content":"\n\nmysterious_variable = 42"}],"entry":"You probably saw us use the `#` sign a few times in earlier exercises.  The `#` sign is for comments. A comment is a line of text that Python won't try to run as code. It's just for humans to read.\n\nComments make your program easier to understand. When you look back at your code or others want to collaborate with you, they can read your comments and easily figure out what your code does.","entry_html":"\u003Cp\u003EYou probably saw us use the \u003Ccode\u003E#\u003C/code\u003E sign a few times in earlier exercises.  The \u003Ccode\u003E#\u003C/code\u003E sign is for comments. A comment is a line of text that Python won\u0026#39;t try to run as code. It\u0026#39;s just for humans to read.\u003C/p\u003E\n\n\u003Cp\u003EComments make your program easier to understand. When you look back at your code or others want to collaborate with you, they can read your comments and easily figure out what your code does.\u003C/p\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"You comment could be something like this:\n\n```python\n# What is the value of mysterious_variable?\n```\n\nNote that if you delete `mysterious_variable`, you may see an error in the console. You can ignore it. ","hint_html":"\u003Cp\u003EYou comment could be something like this:\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode class=\"python\"\u003E# What is the value of mysterious_variable?\n\u003C/code\u003E\u003C/pre\u003E\n\n\u003Cp\u003ENote that if you delete \u003Ccode\u003Emysterious_variable\u003C/code\u003E, you may see an error in the console. You can ignore it. \u003C/p\u003E\n","instruction":"Write a comment on line 1. Make sure it starts with `#`. It can say anything you like.","instruction_html":"\u003Cp\u003EWrite a comment on \u003Ca href=\"javascript:void(0)\" class=\"line-no\" data-from=\"1\" data-to=\"\"\u003Eline 1\u003C/a\u003E. Make sure it starts with \u003Ccode\u003E#\u003C/code\u003E. It can say anything you like.\u003C/p\u003E\n","name":"Single Line Comments","test_functions":"if not '#' in code:\n\treturn \"Did you include a comment in your code?\"\ntry:\n    return True\nexcept SyntaxError: #error may be thrown if the only thing in the code is a comment\n\treturn True","preview_button":false,"is_current_checkpoint":false},{"_id":"4fd2bac8b5ef32000300820b","index":1,"code_reset":true,"default_files":[{"filename":"script.py","content":""}],"entry":"The `#` sign will only comment out a single line. While you could write a multi-line comment, starting each line with `#`, that can be a pain.\n\nInstead, for multi-line comments, you can include the whole block in a set of triple quotation marks:\n\n```\n\"\"\"Sipping from your cup 'til it runneth over,\nHoly Grail.\n\"\"\"\n```","entry_html":"\u003Cp\u003EThe \u003Ccode\u003E#\u003C/code\u003E sign will only comment out a single line. While you could write a multi-line comment, starting each line with \u003Ccode\u003E#\u003C/code\u003E, that can be a pain.\u003C/p\u003E\n\n\u003Cp\u003EInstead, for multi-line comments, you can include the whole block in a set of triple quotation marks:\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode\u003E\u0026quot;\u0026quot;\u0026quot;Sipping from your cup \u0026#39;til it runneth over,\nHoly Grail.\n\u0026quot;\u0026quot;\u0026quot;\n\u003C/code\u003E\u003C/pre\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"Your multiline comment is just a regular phrase or sentence starting with `\"\"\"` and ending with `\"\"\"`. No `#` needed at all!","hint_html":"\u003Cp\u003EYour multiline comment is just a regular phrase or sentence starting with \u003Ccode\u003E\u0026quot;\u0026quot;\u0026quot;\u003C/code\u003E and ending with \u003Ccode\u003E\u0026quot;\u0026quot;\u0026quot;\u003C/code\u003E. No \u003Ccode\u003E#\u003C/code\u003E needed at all!\u003C/p\u003E\n","instruction":"Write a multi-line comment in the editor. It can be any text you'd like!","instruction_html":"\u003Cp\u003EWrite a multi-line comment in the editor. It can be any text you\u0026#39;d like!\u003C/p\u003E\n","name":"Multi-Line Comments","test_functions":"if error:\n\treturn \"Your code looks a bit off. Check the Hint if you need help! Your code threw the following error: \" + str(error)\n\nif not '\"\"\"' in code and not \"'''\" in code:\n\treturn \"Did you remember to write a multi-line comment?\"\n\nreturn True\n","preview_button":false,"is_current_checkpoint":false}],"description":"Good comments make programs more readable and will help you diagnose problems when they arise. Get in the habit of commenting up your code!","name":"Comments","checkpoints_count":2,"completed_checkpoints_count":0,"is_current_project":false,"index":2,"completed":false,"author":{"_id":"4f04f1847057120003006c12","handle":"Eric Weinstein","profile_image_url":"https://codecademy-production.s3.amazonaws.com/profile_thumbnail/50b7d7b3cf6c0f9b11000087_795211733.jpg?AWSAccessKeyId=AKIAI7LDEVVIL32I5WXQ\u0026Expires=1414601607\u0026Signature=bDzdMOBQcYm2P6D4vJ2R6EaXAGc%3D","self_url":"/v1/users/4f04f1847057120003006c12"},"continue_to_section":{"name":"Math Operations","url":"http://www.codecademy.com/courses/introduction-to-python-6WeG3/3?curriculum_id=4f89dab3d788890003000096"}},{"id":"4fd2ab713a16460003005831","checkpoints":[{"_id":"4fd2ab724e68d50003005c5d","index":0,"code_reset":true,"default_files":[{"filename":"script.py","content":"# Set count_to equal to the sum of two big numbers\n\n\n\nprint count_to"}],"entry":"Great! Now let's do some math. You can add, subtract, multiply, divide numbers like this\n\n```python\naddition = 72 + 23\nsubtraction = 108 - 204\nmultiplication = 108 * 0.5\ndivision = 108 / 9\n```","entry_html":"\u003Cp\u003EGreat! Now let\u0026#39;s do some math. You can add, subtract, multiply, divide numbers like this\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode class=\"python\"\u003Eaddition = 72 + 23\nsubtraction = 108 - 204\nmultiplication = 108 * 0.5\ndivision = 108 / 9\n\u003C/code\u003E\u003C/pre\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"Remember, you can set a variable equal to a value with\n\n```python\nvariable_name = # Add your value here!\n```","hint_html":"\u003Cp\u003ERemember, you can set a variable equal to a value with\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode class=\"python\"\u003Evariable_name = # Add your value here!\n\u003C/code\u003E\u003C/pre\u003E\n","instruction":"Set the variable `count_to` equal to the sum of two big numbers.","instruction_html":"\u003Cp\u003ESet the variable \u003Ccode\u003Ecount_to\u003C/code\u003E equal to the sum of two big numbers.\u003C/p\u003E\n","name":"Math","test_functions":"try:\n\tcount_to\nexcept NameError:\n\treturn \"Did you create a variable called count_to?\"\n\nif error:\n\treturn \"Your code looks a bit off. Check the Hint if you need help! Your code threw the following error: \" + str(error)\n\nif not '+' in code:\n\treturn \"Did you remember to use 30 + 50 in your code?\"\n\nif count_to \u003C= 3:\n\treturn \"Add two big numbers that sum to more than %s.\" % str(count_to)\n\nreturn True\n","preview_button":false,"is_current_checkpoint":false},{"_id":"4fd2c374f361fd000300094e","index":1,"code_reset":true,"default_files":[{"filename":"script.py","content":"#Set eggs equal to 100 using exponentiation on line 3!\n\neggs =\n\nprint eggs"}],"entry":"All that math can be done on a calculator, so why use Python? Because you can combine math with other data types (e.g. **booleans**) and commands to create useful programs. Calculators just stick to numbers. \n\nNow let's work with exponents.\n\n```\neight = 2 ** 3\n```\n\nIn the above example, we create a new variable called `eight` and set it to `8`, or the result of 2 to the power to 3 (2^3).\n\nNotice that we use `**` instead of `*` or the multiplication operator.","entry_html":"\u003Cp\u003EAll that math can be done on a calculator, so why use Python? Because you can combine math with other data types (e.g. \u003Cstrong\u003Ebooleans\u003C/strong\u003E) and commands to create useful programs. Calculators just stick to numbers. \u003C/p\u003E\n\n\u003Cp\u003ENow let\u0026#39;s work with exponents.\u003C/p\u003E\n\n\u003Cpre\u003E\u003Ccode\u003Eeight = 2 ** 3\n\u003C/code\u003E\u003C/pre\u003E\n\n\u003Cp\u003EIn the above example, we create a new variable called \u003Ccode\u003Eeight\u003C/code\u003E and set it to \u003Ccode\u003E8\u003C/code\u003E, or the result of 2 to the power to 3 (2^3).\u003C/p\u003E\n\n\u003Cp\u003ENotice that we use \u003Ccode\u003E**\u003C/code\u003E instead of \u003Ccode\u003E*\u003C/code\u003E or the multiplication operator.\u003C/p\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":null,"hint_html":null,"instruction":"Create a new variable called `eggs` and use exponents to set `eggs` equal 100.\n\nTry raising 10 to the power of 2.","instruction_html":"\u003Cp\u003ECreate a new variable called \u003Ccode\u003Eeggs\u003C/code\u003E and use exponents to set \u003Ccode\u003Eeggs\u003C/code\u003E equal 100.\u003C/p\u003E\n\n\u003Cp\u003ETry raising 10 to the power of 2.\u003C/p\u003E\n","name":"Exponentiation","test_functions":"if error:\n    return \"Your code looks a bit off. Check the Hint if you need help! Your code threw the following error: \" + str(error)\n\nif not '**' in code:\n\treturn \"Did you use ** in your code?\"\ntry:\n    if eggs != 100:\n        return \"It looks like eggs is %s instead of 100.\" % str(eggs)\nexcept NameError as ne:\n    return \"Make sure eggs is properly defined! Your code threw the following NameError: \" + str(ne)\nexcept Exception as e:\n    return \"Your code threw the following error: \" + str(e)\nreturn True\n","preview_button":false,"is_current_checkpoint":false},{"_id":"4fd2c37b7d163d0003000ad9","index":2,"code_reset":true,"default_files":[{"filename":"script.py","content":"#Set spam equal to 1 using modulo on line 3!\n\nspam =\n\nprint spam"}],"entry":"Our final operator is **modulo**. **Modulo** returns the remainder from a division. So, if you type `3 % 2`, it will return `1`, because 2 goes into 3 evenly once, with 1 left over.","entry_html":"\u003Cp\u003EOur final operator is \u003Cstrong\u003Emodulo\u003C/strong\u003E. \u003Cstrong\u003EModulo\u003C/strong\u003E returns the remainder from a division. So, if you type \u003Ccode\u003E3 % 2\u003C/code\u003E, it will return \u003Ccode\u003E1\u003C/code\u003E, because 2 goes into 3 evenly once, with 1 left over.\u003C/p\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"Any odd number `% 2` will equal 1 (since dividing any odd number by 2 always leaves 1 as a remainder).\n\nRemember that you can't divide by 0 or you will get an error. Same goes for `%`. `10 % 0` will cause an error!","hint_html":"\u003Cp\u003EAny odd number \u003Ccode\u003E% 2\u003C/code\u003E will equal 1 (since dividing any odd number by 2 always leaves 1 as a remainder).\u003C/p\u003E\n\n\u003Cp\u003ERemember that you can\u0026#39;t divide by 0 or you will get an error. Same goes for \u003Ccode\u003E%\u003C/code\u003E. \u003Ccode\u003E10 % 0\u003C/code\u003E will cause an error!\u003C/p\u003E\n","instruction":"Use modulo to set `spam` equal to `1`. You can use any two numbers that will leave a remainder of `1` to do this.","instruction_html":"\u003Cp\u003EUse modulo to set \u003Ccode\u003Espam\u003C/code\u003E equal to \u003Ccode\u003E1\u003C/code\u003E. You can use any two numbers that will leave a remainder of \u003Ccode\u003E1\u003C/code\u003E to do this.\u003C/p\u003E\n","name":"Modulo","test_functions":"if error:\n    return \"Your code looks a bit off. Check the Hint if you need help! Your code threw the following error: \" + str(error)\n\nif not '%' in code:\n\treturn \"Make sure to use % in your code.\"\ntry:\n    if spam != 1:\n        return \"It looks like spam is %s instead of 1.\" % str(spam)\nexcept NameError as ne:\n    return \"Make sure spam is properly defined! Your code threw the following NameError: \" + str(ne)\nexcept Exception as e:\n    return \"Your code threw the following error: \" + str(e)\n\nreturn True\n","preview_button":false,"is_current_checkpoint":false}],"description":"If all we could do in Python were declare variables and write comments, it wouldn't be very exciting. Thankfully, that's not the case\u2014we can combine and manipulate data to create powerful, flexible programs to suit our needs.","name":"Math Operations","checkpoints_count":3,"completed_checkpoints_count":0,"is_current_project":false,"index":3,"completed":false,"author":{"_id":"4f04f1847057120003006c12","handle":"Eric Weinstein","profile_image_url":"https://codecademy-production.s3.amazonaws.com/profile_thumbnail/50b7d7b3cf6c0f9b11000087_795211733.jpg?AWSAccessKeyId=AKIAI7LDEVVIL32I5WXQ\u0026Expires=1414601607\u0026Signature=bDzdMOBQcYm2P6D4vJ2R6EaXAGc%3D","self_url":"/v1/users/4f04f1847057120003006c12"},"continue_to_section":{"name":"Review","url":"http://www.codecademy.com/courses/introduction-to-python-6WeG3/4?curriculum_id=4f89dab3d788890003000096"}},{"id":"4fd2ab977f4af30003005714","checkpoints":[{"_id":"4fd2ab984f76ab0003005dcf","index":0,"code_reset":true,"default_files":[{"filename":"script.py","content":""}],"entry":"Nice work! So far, you've learned about:\n* **Variables**, which store values for later use\n* **Data types**, such as numbers and booleans\n* **Whitespace**, which separates statements\n* **Comments**, which make your code easier to read\n* **Arithmetic operations**, including `+`, `-`, `*`, `/`, `**`, and `%`","entry_html":"\u003Cp\u003ENice work! So far, you\u0026#39;ve learned about:\u003C/p\u003E\n\n\u003Cul\u003E\n\u003Cli\u003E\u003Cstrong\u003EVariables\u003C/strong\u003E, which store values for later use\u003C/li\u003E\n\u003Cli\u003E\u003Cstrong\u003EData types\u003C/strong\u003E, such as numbers and booleans\u003C/li\u003E\n\u003Cli\u003E\u003Cstrong\u003EWhitespace\u003C/strong\u003E, which separates statements\u003C/li\u003E\n\u003Cli\u003E\u003Cstrong\u003EComments\u003C/strong\u003E, which make your code easier to read\u003C/li\u003E\n\u003Cli\u003E\u003Cstrong\u003EArithmetic operations\u003C/strong\u003E, including \u003Ccode\u003E+\u003C/code\u003E, \u003Ccode\u003E-\u003C/code\u003E, \u003Ccode\u003E*\u003C/code\u003E, \u003Ccode\u003E/\u003C/code\u003E, \u003Ccode\u003E**\u003C/code\u003E, and \u003Ccode\u003E%\u003C/code\u003E\u003C/li\u003E\n\u003C/ul\u003E\n","external_resources":["https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"],"hint":"You can use arithmetic operators directly on variables! Remember, `python` squared means `python ** 2`.\n\nNote that the name of the variable `monty_python` has nothing to do with the name of the variables `monty` and `python`. We just decided to use these variable names because Python people love Monty Python's Flying Circus!","hint_html":"\u003Cp\u003EYou can use arithmetic operators directly on variables! Remember, \u003Ccode\u003Epython\u003C/code\u003E squared means \u003Ccode\u003Epython ** 2\u003C/code\u003E.\u003C/p\u003E\n\n\u003Cp\u003ENote that the name of the variable \u003Ccode\u003Emonty_python\u003C/code\u003E has nothing to do with the name of the variables \u003Ccode\u003Emonty\u003C/code\u003E and \u003Ccode\u003Epython\u003C/code\u003E. We just decided to use these variable names because Python people love Monty Python\u0026#39;s Flying Circus!\u003C/p\u003E\n","instruction":"Let's put our knowledge to work.\n\n1. Write a single-line comment on line 1. It can be anything! (Make sure it starts with `#`)\n2. Set the variable `monty` equal to `True`.\n3. Set another variable `python` equal to `1.234`.\n4. Set a third variable `monty_python` equal to `python` squared.","instruction_html":"\u003Cp\u003ELet\u0026#39;s put our knowledge to work.\u003C/p\u003E\n\n\u003Col\u003E\n\u003Cli\u003EWrite a single-line comment on \u003Ca href=\"javascript:void(0)\" class=\"line-no\" data-from=\"1\" data-to=\"\"\u003Eline 1\u003C/a\u003E. It can be anything! (Make sure it starts with \u003Ccode\u003E#\u003C/code\u003E)\u003C/li\u003E\n\u003Cli\u003ESet the variable \u003Ccode\u003Emonty\u003C/code\u003E equal to \u003Ccode\u003ETrue\u003C/code\u003E.\u003C/li\u003E\n\u003Cli\u003ESet another variable \u003Ccode\u003Epython\u003C/code\u003E equal to \u003Ccode\u003E1.234\u003C/code\u003E.\u003C/li\u003E\n\u003Cli\u003ESet a third variable \u003Ccode\u003Emonty_python\u003C/code\u003E equal to \u003Ccode\u003Epython\u003C/code\u003E squared.\u003C/li\u003E\n\u003C/ol\u003E\n","name":"Bringing It All Together","test_functions":"try:\n\tmonty\nexcept NameError:\n\treturn \"Did you create a variable called monty?\"\n\ntry: \n\tpython\nexcept NameError:\n\treturn \"Did you create a variable called python?\"\n\ntry:\n\tmonty_python\nexcept NameError:\n\treturn \"Did you create a variable called monty_python?\"\n\nif error:\n\treturn \"Your code looks a bit off. Feel free to peek back at earlier exercises if you need help! Your code threw the following error: \" + str(error)\n\nif not '#' in code:\n\treturn \"Did you remember to add your comment on line 1?\"\n\nif not (monty is True):\n\treturn \"Did you set the monty variable to True?\"\n\nif python != 1.234:\n\treturn \"It looks like python is %s instead of 1.234.\" % str(python)\n\nif monty_python != python ** 2:\n\treturn \"It looks like monty_python is not equal to python squared.\"\n\nreturn True\n","preview_button":false,"is_current_checkpoint":false}],"description":"Rock on! Let's take a minute to review what you've learned.","name":"Review","checkpoints_count":1,"completed_checkpoints_count":0,"is_current_project":false,"index":4,"completed":false,"author":{"_id":"4f04f1847057120003006c12","handle":"Eric Weinstein","profile_image_url":"https://codecademy-production.s3.amazonaws.com/profile_thumbnail/50b7d7b3cf6c0f9b11000087_795211733.jpg?AWSAccessKeyId=AKIAI7LDEVVIL32I5WXQ\u0026Expires=1414601607\u0026Signature=bDzdMOBQcYm2P6D4vJ2R6EaXAGc%3D","self_url":"/v1/users/4f04f1847057120003006c12"},"continue_to_course":{"name":"Tip Calculator","url":"http://www.codecademy.com/courses/python-beginner-GB6hM/?curriculum_id=4f89dab3d788890003000096"}}],"mode":"cli","language":"Python","is_php":false,"return_to":{"name":"Python","url":"http://www.codecademy.com/en/tracks/python"},"project_index":0,"course_progress_percentage":0,"course_exercises_index":1,"course_exercises_total":13,"continue_to_course":{"name":"Tip Calculator","url":"http://www.codecademy.com/courses/python-beginner-GB6hM/?curriculum_id=4f89dab3d788890003000096"},"author":{"_id":"4f04f1847057120003006c12","handle":"Eric Weinstein","profile_image_url":"https://codecademy-production.s3.amazonaws.com/profile_thumbnail/50b7d7b3cf6c0f9b11000087_795211733.jpg?AWSAccessKeyId=AKIAI7LDEVVIL32I5WXQ\u0026Expires=1414601607\u0026Signature=bDzdMOBQcYm2P6D4vJ2R6EaXAGc%3D","self_url":"/v1/users/4f04f1847057120003006c12"}};
  CCDATA.composer.current_checkpoint_index = 0;
  CCDATA.composer.intro = true;
  CCDATA.composer.lintHintShown = {};
</script>
<header class="main">
  
    <div >

<a href="http://www.codecademy.com/en/tracks/python" class="lesson__back-nav ui-header__link fl">
  <div class="ui-media lesson__track-wrapper">
    <div class="ui-media__image">
      <div class="new-icon new-icon--medium new-icon--back-arrow"></div>
    </div>
    <div class="ui-media__main">
        Python
    </div>
  </div>
</a>
<h1 class="logo">
  <a href="/" class="ui-header__logo--rebrand">
    <img alt="Codecademy" src="http://cdn-production.codecademy.com/assets/logo/logo--teal-d10b21a45b84379f184aa74fbd19ab8c.svg" />
</a></h1>

<div class="ui-header__me lesson__me-wrapper">
  <a href="#" class="ui-header__link ui-media" data-toggle="dropdown" data-target="#user-menu">
  <div class="ui-media__image">
    <img alt="wanpyo" class="ui-header__avatar" src="http://www.gravatar.com/avatar/bdfe58b3b6965816e1a16470a98cc71a?s=140&amp;d=retro" />
  </div>
  <div class="ui-media__main">
    Me <span class="ui-button__dropdown-arrow"></span>
  </div>
</a>
<div id="user-menu" class="app__user-menu ui-dropdown ui-dropdown--light ui-dropdown--checkpoints ui-dropdown--arrow-on-top">
<div class="ui-dropdown__arrow__container"><div class="ui-dropdown__arrow"></div><div class="ui-dropdown__arrow-border__container"><div class="ui-dropdown__arrow-border"></div></div></div>
  <div class="block-list">
    <a href="/users/wanpyo" class="block-list__item">View my profile</a>
    <a href="/users/54510d5f80ff3310580002c5/edit" class="block-list__item">Edit account settings</a>
    <a href="/help" class="block-list__item" id="help-nav">Help</a>
    <a href="/sign_out" class="block-list__item">Sign out</a>
  </div>
</div>

</div>
<div id="connection-state">
  <div class="msg"></div>
</div>
<div id="notices"></div>
</div>

</header>
<div class="ui-overlay ui-overlay--dark ui-overlay--lesson js-lesson-loading-overlay is-shown">
  <img alt="Ajax-loader-large-white" class="loader" src="http://cdn-production.codecademy.com/assets/ajax-loader-large-white-d4ed9d7ce3211d967fd1285cd84a1734.gif" />
</div>
<div >
<div class="lesson-left-bar" >
  <div class="js-lesson-left-bar">
      <div class="lesson-nav ui-dropdown ui-dropdown--light ui-dropdown--checkpoints ui-dropdown--arrow-on-top js-checkpoints">
  <div class="ui-dropdown__arrow__container">
    <div class="ui-dropdown__arrow"></div>
    <div class="ui-dropdown__arrow-border__container">
      <div class="ui-dropdown__arrow-border"></div>
    </div>
  </div>

  <div class="block-list ui-counter ui-counter--bold">
    <a class="block-list__item ui-media ui-media--reverse lesson-nav__section js-section is-active">
      <div class="ui-media__image">
      </div>
      <div class="ui-media__main">
        Variables and Data Types
      </div>
    </a>
    <div class="js-section__content" data-index="0">
      <div class="block-list lesson-nav__exercises">
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="0">
          <div class="ui-media__image new-icon new-icon--small
           new-icon--checkpoint--current
">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              <strong>Welcome!</strong>
            </div>
          </div>
        </a>
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="1">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Variables
            </div>
          </div>
        </a>
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="2">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Booleans
            </div>
          </div>
        </a>
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="3">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              You&#39;ve Been Reassigned
            </div>
          </div>
        </a>
      </div>
    </div>
    <a class="block-list__item ui-media ui-media--reverse lesson-nav__section js-section">
      <div class="ui-media__image">
      </div>
      <div class="ui-media__main">
        Whitespace and Statements
      </div>
    </a>
    <div class="js-section__content" data-index="1">
      <div class="block-list lesson-nav__exercises">
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="0">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Whitespace
            </div>
          </div>
        </a>
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="1">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Whitespace Means Right Space
            </div>
          </div>
        </a>
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="2">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              A Matter of Interpretation
            </div>
          </div>
        </a>
      </div>
    </div>
    <a class="block-list__item ui-media ui-media--reverse lesson-nav__section js-section">
      <div class="ui-media__image">
      </div>
      <div class="ui-media__main">
        Comments
      </div>
    </a>
    <div class="js-section__content" data-index="2">
      <div class="block-list lesson-nav__exercises">
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="0">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Single Line Comments
            </div>
          </div>
        </a>
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="1">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Multi-Line Comments
            </div>
          </div>
        </a>
      </div>
    </div>
    <a class="block-list__item ui-media ui-media--reverse lesson-nav__section js-section">
      <div class="ui-media__image">
      </div>
      <div class="ui-media__main">
        Math Operations
      </div>
    </a>
    <div class="js-section__content" data-index="3">
      <div class="block-list lesson-nav__exercises">
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="0">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Math
            </div>
          </div>
        </a>
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="1">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Exponentiation
            </div>
          </div>
        </a>
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="2">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Modulo
            </div>
          </div>
        </a>
      </div>
    </div>
    <a class="block-list__item ui-media ui-media--reverse lesson-nav__section js-section">
      <div class="ui-media__image">
      </div>
      <div class="ui-media__main">
        Review
      </div>
    </a>
    <div class="js-section__content" data-index="4">
      <div class="block-list lesson-nav__exercises">
        <a class="block-list__item ui-media lesson-nav__exercise js-switch-checkpoint" data-index="0">
          <div class="ui-media__image new-icon new-icon--small
          
            
             new-icon--checkpoint
          ">
          </div>
          <div class="ui-media__main">
            <div class="ui-counter__item">
              Bringing It All Together
            </div>
          </div>
        </a>
      </div>
    </div>
    <div class="block-list__item">
      <div class="lesson-nav__meta">Course by Eric Weinstein</div>
    </div>
  </div>
</div><div class="ui-overlay ui-overlay--dark js-checkpoints-overlay"></div>
<div class="lesson-left-bar__header">

  <div class="article__inner">
    <a class="ui-button ui-button--small ui-button--round ui-button--transparent lesson__show-checkpoints js-show-checkpoints">
      1/13
      <div class="ui-button__dropdown-arrow"></div>
    </a>
    <div class="lesson__course-name one-line-text js-course-name">Python Syntax</div>
    <div class="lesson-left-bar__toggle js-toggle-left-bar">
      <div class="new-icon--small new-icon--arrow-right"></div>
    </div>
  </div>
</div>
<div class="lesson-checkpoint__wrapper">
  <div class="lesson-checkpoint nano">
    <div class="nano__content content">
      <div class="lesson-checkpoint__inner">
        <div class="article__inner">
          <div class="article__header">
            <div class="lesson-checkpoint__name">Welcome!</div>
          </div>
          <div class="article__content">
            <p>Python is an easy to learn programming language. You can use it to create web apps, games, even a search engine!</p>

<p>Ready to learn Python? Click Save &amp; Submit Code to continue!</p>

          </div>
        </div>
        <div class="lesson-checkpoint__instructions">
          <div class="article__inner lesson-checkpoint__instructions__header">
            <div class="block-label--light-blue">Instructions</div>
          </div>
          <div class="article__inner">
            <p>Ready to learn Python? Click Save &amp; Submit Code to continue!</p>

              <div class="ui-accordian ui-accordian--lesson">
                <div class="ui-accordian__inner">
                  <a href="#" class="ui-accordian__trigger ui-media">
                    <div class="ui-media__image new-icon--small new-icon--center new-icon--circle--blue">?</div>
                    <div class="ui-media__main">
                      <span class="is-hidden-if-is-expanded"><b>Stuck?</b> Get a hint!</span>
                      <span class="is-shown-if-is-expanded--inline"><b>Hint</b></span>
                    </div>
                  </a>
                  <div class="ui-accordian__content has-markdown">
                    <p>If the loading bar fills but doesn&#39;t fade away, try refreshing the page.</p>

                  </div>
                </div>
              </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

  </div>
    <div class="lesson-links">
  <a target="_blank" class="lesson-links__link" href="/forums/introduction-to-python-6WeG3/0">Q&A Forum</a>
  <a target="_blank" class="lesson-links__link" href="/glossary/python">Glossary</a>
</div>
</div>
<div class="lesson-middle js-lesson-editor" >
  <div class="waiting-overlay"></div>
  <div class="lesson-file-tabs js-lesson-file-tabs">
  <div class="lesson-middle__container lesson-editor-width">
    <div class="lesson-file-tabs__wrapper">
      <div>
          <div class="lesson-file-tabs__tab js-file-tab tab cf" data-type="script.py">
            <div class="new-icon--small--center new-icon--lesson-file fl"></div>
            <div class="fl">script.py</div>
          </div>      </div>
      <div id="composer-view-project-button-for-narrow-screen">
      </div>
    </div>
  </div>
</div>
<div class="lesson-ace-editor lesson-editor-width js-ace-editor orion-composer"></div>
<div class="file-container"></div>
</div>
<div class="lesson-sidebar lesson-sidebar--composer-responsive js-lesson-sidebar" >
  <div class="lesson-sidebar-container">
    
<div class="result-chrome">
  <div class="js-server-status-container"></div>
  <div class="terminal terminal-right">
    <div class="result-container console"></div>
  </div>
</div>




    <div id="js-glossary-flash-card" class="glossary-flash-card glossary-flash-card--hidden"></div>
    <div id="js-backtest" class="backtest backtest--hidden"></div>
  </div>
</div>
<div class="lesson-action-bar js-lesson-action-bar">
  <div class="composer-bottom-bar lesson-action-bar__inner">
  <div class="button-group--horizontal">
    <a class="ui-button ui-button--medium ui-button--blue--on-dark ui-loading js-submit-code">
      <div class="ui-loading__other">
        Save & Submit Code
      </div>
      <div class="ui-loading__image new-icon--small new-icon--gear--white loading-spin"></div>
    </a>
    <a class="ui-button ui-button--medium ui-button--transparent--on-dark js-reset-code reset">Reset Code</a>
  </div>
</div>
<div class="lesson-action-bar__state lesson-action-bar__inner lesson-action-bar__inner--pass js-state--passed"></div>
<div class="lesson__state lesson__state--failed js-state--failed"></div>
<div class="lesson-action-bar__state lesson-action-bar__state--back lesson-action-bar__inner js-state--back">
  <a class="ui-button ui-button--medium ui-button--gray--on-dark js-back-to-editor back-editor">Back to Editor</a>
</div>
</div>

<!-- Facebook Publishing permissions form -->

<form accept-charset="UTF-8" action="/users/54510d5f80ff3310580002c5" class="edit_user" data-remote="true" id="enable-facebook-publishing" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="_method" type="hidden" value="put" /><input name="authenticity_token" type="hidden" value="A7C8RXnQs93rCz/IUw4qCFrV08Lm/DRwSii/18epq7I=" /></div>
  <input id="user_fb_pa" name="user[fb_pa]" type="hidden" value="true" />
</form><form accept-charset="UTF-8" action="/users/54510d5f80ff3310580002c5" class="edit_user" data-remote="true" id="disable-facebook-publishing" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="_method" type="hidden" value="put" /><input name="authenticity_token" type="hidden" value="A7C8RXnQs93rCz/IUw4qCFrV08Lm/DRwSii/18epq7I=" /></div>
  <input id="user_fb_pa" name="user[fb_pa]" type="hidden" value="false" />
</form>

</div>

</body>
<script src="http://cdn-production.codecademy.com/assets/templates/common-en-e9e653be7215c84704beb770449e942f.js" type="text/javascript"></script>

  <script src="http://cdn-production.codecademy.com/assets/dist/common-d984c8d0fbe4629491c83d22da359fce.js" type="text/javascript"></script>
  <script src="http://cdn-production.codecademy.com/assets/dist/controllers/composer_controller-a8659c5b4b92c1260d20594bfd12405c.js" type="text/javascript"></script>

  <!-- Qualaroo -->
  <script type="text/javascript">
    var _kiq = _kiq || [];
    _kiq.push(['identify', '54510d5f80ff3310580002c5']);
    _kiq.push(['set', {
      'client_ip':'1.214.231.193'
    }]);
  </script>

  <!-- Chartbeat -->
  <script>
    var _sf_async_config={uid:27714,domain:"codecademy.com"};
    (function(){
      function loadChartbeat() {
        window._sf_endpt=(new Date()).getTime();
        var e = document.createElement('script');
        e.setAttribute('language', 'javascript');
        e.setAttribute('type', 'text/javascript');
        e.setAttribute('src',
        (("https:" == document.location.protocol) ? "https://a248.e.akamai.net/chartbeat.download.akamai.com/102508/" : "http://static.chartbeat.com/") +
        "js/chartbeat.js");
        document.body.appendChild(e);
      }
      var oldonload = window.onload;
      window.onload = (typeof window.onload != 'function') ?
      loadChartbeat : function() { oldonload(); loadChartbeat(); };
    })();
  </script>


<!-- Load relevant javascript controller -->
<script type="text/javascript">
  require(['common', 'controllers/composer_controller'], function (common, controller) {
    if (common) common.init();
    if (controller) controller['init']();
    
  });
  var registration_partial = registration_partial || false;
  if (registration_partial) {
    require(["controllers/registrations_controller"], function (controller) {
      controller.init();
    });
  }
  CCDATA.authenticity_token = 'A7C8RXnQs93rCz/IUw4qCFrV08Lm/DRwSii/18epq7I=';
</script>

<!-- Facebook -->
<div id="fb-root"></div>
<script>
  var FB_APP_ID = '212500508799908';
  window.fbAsyncInit = function() {
    var FB = (window.FB || undefined);
    if (FB) {
      FB.init({
        appId      : FB_APP_ID
      , channelUrl : window.root_url+'/channel.html'
      , status     : true
      , cookie     : true
      , xfbml      : true
      });
    }
  };

  (function(d){
    var js, id = 'facebook-jssdk', ref = d.getElementsByTagName('script')[0];
    if (d.getElementById(id)) {return;}
    js = d.createElement('script'); js.id = id; js.async = true;
    js.src = "//connect.facebook.net/en_US/all.js";
    ref.parentNode.insertBefore(js, ref);
  }(document));
</script>

<!-- Overlay laoder. Deprecated by rebrand? -->
<script>
  var overlay = document.getElementById('overlay');
  if (overlay && overlay.children.length > 0) {
    overlay.style.cssText = "display: block;";
  }
</script>
</html>