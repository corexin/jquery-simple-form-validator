#simple jquery plugin to validate html form, super easy to use

# Introduction #

I created it when helping my friends design a website, going through a few other validation frameworks, I felt it should be a simple step to validate html form, which my simple plugin can realize.

Its not completed yet, but easy for other javascript developers to add more.

# Details #

Usage
  * include the script in your html/jsp/php file
  * add :required as class to the input,textarea field, e.g. 

&lt;input class=":required" /&gt;


  * add '#submitButtonId').bind('click', function(event) {return $("#formToValidateId").simpleValidate(); });