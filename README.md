# hello-world
Hi, I am Noushin Iqra and I love coding :)

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>iphoneApp</title>

    <!-- Bootstrap -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" 
     integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

    <link href="https://fonts.googleapis.com/css?family=Abel|Patrick+Hand+SC|Satisfy|Walter+Turncoat" rel="stylesheet">

    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" 
     integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">

    <!-- JQuery -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" 
    crossorigin="anonymous"></script>

    <script type="text/javascript">
        $(document).ready(function(){

            $("#menu-btn").click(function() {
                $(".menu").slideToggle("fast");
            });

            $("#pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide(); //Hide all content
            $("#pills-1").show(); //Show first tab content

            $("#nav1").on('click', function() {
                $("#pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-1").show();
            });

            $("#nav2").on('click', function() {
                $("#pills-1, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-2").show();
            });

            $("#nav3").on('click', function() {
                $("#pills-1, #pills-2, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-3").show();
            });

            $("#nav4").on('click', function() {
                $("#pills-1, #pills-2, #pills-3, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-4").show();
            });

            $("#nav5").on('click', function() {
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-5").show();
            });

            $("#nav6").on('click', function() {
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-7, #pills-8, #pills-9, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-6").show();
            });

            $("#nav7").on('click', function() {
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-8, #pills-9, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-7").show();
            });

            $("#nav8").on('click', function() {
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-9, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-8").show();
            });

            $("#nav9").on('click', function() {
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-9").show();
            });

            $("#nav10").on('click', function() {
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-10").show();
            });//navbars

            
            $("#list2-content1").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill2-content1").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list2-content2").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill2-content2").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list2-content3").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill2-content3").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list2-content4").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill2-content4").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list2-content5").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill2-content5").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list2-content6").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill2-content6").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list2-content7").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill2-content7").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list2-content8").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill2-content8").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list3-content1").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill3-content1").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list3-content2").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill3-content2").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list4-content1").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill4-content1").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list5-content1").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill5-content1").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list5-content2").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill5-content2").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list5-content3").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill5-content3").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list6-content1").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill6-content1").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list6-content2").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill6-content2").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list6-content3").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill6-content3").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list6-content4").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill6-content4").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list7-content1").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill7-content1").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list7-content2").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill7-content2").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list7-content3").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill7-content3").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list8-content1").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill8-content1").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list9-content1").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill9-content1").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list9-content2").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill9-content2").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list10-content1").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill10-content1").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list10-content2").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill10-content2").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $("#list10-content3").click(function(){
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9, #pills-10").hide();
                $("#tab_details").addClass("active").show(); //Activate tab details
                $("#pill1-content1, #pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2, #pill10-content1, #pill10-content2, #pill10-content3").hide();
                $("#pill10-content3").animate({
                    width: "toggle"
                }, 220);
            });//slide effect

            $(".goback1").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-1").show();
            });

            $(".goback2").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-2").show();
            });

            $(".goback3").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-3").show();
            });

            $(".goback4").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-4").show();
            });

            $(".goback5").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-5").show();
            });

            $(".goback6").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-6").show();
            });

            $(".goback7").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-7").show();
            });

            $(".goback8").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-8").show();
            });

            $(".goback9").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-9").show();
            });

            $(".goback10").click(function() {
                $("#pill2-content1, #pill2-content2, #pill2-content3, #pill2-content4, #pill2-content5," +
                " #pill2-content6, #pill2-content7, #pill2-content8, #pill3-content1, #pill3-content2, #pill4-content1," +
                " #pill5-content1, #pill5-content2, #pill5-content3, #pill6-content1, #pill6-content2, #pill6-content3, #pill6-content4," +
                " #pill7-content1, #pill7-content2, #pill7-content3, #pill8-content1, #pill9-content1, #pill9-content2," +
                " #pill10-content1, #pill10-content2, #pill10-content3").animate({ 
                    width: "toggle"
                });
                $("#tab_details").hide();
                $("#pills-10").show();
            });

            $(".subscribe").click(function() {
                $("#tab_details").hide();
                $("#subscription-form").show();
            });

            $("#home").click(function() {
                $("#pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9," +
                " #pills-10, #tab_details, .menu, #subscription-form, #footer-content").hide();
                $("#pills-1").show();
            });

            $("#notification").click(function() {
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9," +
                " #pills-10, #tab_details, .menu, #subscription-form, #footer-content, #setting-div").hide();
                $("#footer-content").addClass("active").show(); //Activate tab details
                $("#notification-div, #list-div, #setting-div").hide();
                $("#notification-div").slideDown("fast");
            });

            $("#list").click(function() {
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9," +
                " #pills-10, #tab_details, .menu, #subscription-form, #footer-content, #setting-div").hide();
                $("#footer-content").addClass("active").show(); //Activate tab details
                $("#notification-div, #list-div, #setting-div").hide();
                $("#list-div").slideDown("fast");
            });

            $("#setting").click(function() {
                $("#pills-1, #pills-2, #pills-3, #pills-4, #pills-5, #pills-6, #pills-7, #pills-8, #pills-9," +
                " #pills-10, #tab_details, .menu, #subscription-form, #footer-content, #setting-div").hide();
                $("#footer-content").addClass("active").show(); //Activate tab details
                $("#notification-div, #list-div, #setting-div").hide();
                $("#setting-div").slideDown("fast");
            });

        });
    </script>
  
    <!-- CSS -->
    <link rel="stylesheet" href="style.css">

</head>

<body>
<header style="background-color: lightgrey;">
        <div class="container">    
            <div class="row text-center">
                    <div class="col-xs-2 hamburger blue" id="divHeader">
                        <button type="button" class="btn" id="menu-btn">
                                <i class="fa fa-bars" aria-hidden="true" style="color: black;"></i> 
                        </button>
                    </div>
                    <div class="col-xs-10 green" style="height: 75px; padding-top: 5px;">       
                        <h1 class="red"><span style="font-size: 12px;">SUPERVISION</span><b>CommunicationHub</b></h1> 
                    </div> 
                    <div class="menu">
                            <ul>
                              <a href="#"><li>LINK ONE</li></a>
                              <a href="#"><li>LINK TWO</li></a>
                              <a href="#"><li>LINK THREE</li></a>
                              <a href="#"><li>LINK FOUR</li></a>
                            </ul>
                    </div>                
            </div>
        </div>      

<div class="container" id="navbar"> 
    <div class="row" style="background-color:white;">
        <div id="navCarousel" class="carousel slide" data-interval="false" data-ride="carousel">
        
            <div class="carousel-inner text-center">
                
                <ul class="nav nav-pills nav-jutified item text-center active" role="tablist" id="activeNav">
                      <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item active" id="nav1">
                            <a class="nav-link" id="pills-home-tab" data-toggle="pill" href="#pills-1" role="tab" aria-controls="pills-1" aria-selected="true">
                                    <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                    class="img-circle" width=40 height=40/>
                            </a>
                        </li></div>  
                        <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item" id="nav2">
                            <a class="nav-link" data-toggle="pill" href="#pills-2" role="tab" aria-controls="pills-2" aria-selected="false">
                                <img alt="Brand" src="https://static.pexels.com/photos/36753/flower-purple-lical-blosso.jpg" 
                                class="img-circle" width=40 height=40/>
                            </a>
                        </li></div>
                        <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item" id="nav3">
                            <a class="nav-link" data-toggle="pill" href="#pills-3" role="tab" aria-controls="pills-3" aria-selected="false">
                                    <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                    class="img-circle" width=40 height=40/>
                            </a>
                        </li></div>
                        <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item" id="nav4">
                            <a class="nav-link" data-toggle="pill" href="#pills-4" role="tab" aria-controls="pills-4" aria-selected="false">
                                    <img alt="Brand" src="https://static.pexels.com/photos/36753/flower-purple-lical-blosso.jpg" 
                                    class="img-circle" width=40 height=40/>
                            </a>                                   
                        </li></div>
                        <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item" id="nav5">
                            <a class="nav-link" data-toggle="pill" href="#pills-5" role="tab" aria-controls="pills-5" aria-selected="false">
                                    <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                    class="img-circle" width=40 height=40/>
                            </a>
                        </li></div>
                </ul>

                <ul class="nav nav-pills nav-jutified item text-center" role="tablist">
                        <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item" id="nav6">
                            <a class="nav-link" data-toggle="pill" href="#pills-6" role="tab" aria-controls="pills-6" aria-selected="false">
                                    <img alt="Brand" src="https://static.pexels.com/photos/36753/flower-purple-lical-blosso.jpg" 
                                    class="img-circle" width=40 height=40/>
                            </a>
                        </li></div>
                        <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item" id="nav7">
                            <a class="nav-link" data-toggle="pill" href="#pills-7" role="tab" aria-controls="pills-7" aria-selected="false">
                                    <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                    class="img-circle" width=40 height=40/>
                            </a>
                        </li></div>
                        <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item" id="nav8">
                            <a class="nav-link" data-toggle="pill" href="#pills-8" role="tab" aria-controls="pills-8" aria-selected="false">
                                    <img alt="Brand" src="https://static.pexels.com/photos/36753/flower-purple-lical-blosso.jpg" 
                                    class="img-circle" width=40 height=40/>
                            </a>
                        </li></div>
                        <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item" id="nav9">
                            <a class="nav-link" data-toggle="pill" href="#pills-9" role="tab" aria-controls="pills-9" aria-selected="false">
                                    <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                    class="img-circle" width=40 height=40/>
                            </a>
                        </li></div>
                        <div class="col-2 col-xs-2 col-sm-2 col-md-2 shift-right"><li class="nav-item" id="nav10">
                            <a class="nav-link" data-toggle="pill" href="#pills-10" role="tab" aria-controls="pills-10" aria-selected="false">
                                    <img alt="Brand" src="https://static.pexels.com/photos/36753/flower-purple-lical-blosso.jpg" 
                                    class="img-circle" width=40 height=40/>
                            </a>
                        </li></div>                      
                </ul>

            </div>

            
                <a class="right carousel-control" href="#navCarousel" data-slide="next">
                    <span class="glyphicon glyphicon-chevron-right"></span>
                    <span class="sr-only">Next</span>
                </a>

        </div>
    </div>
</div><!--container navbar-->

</header> 

<main>
    <div class="container" id="tab_content">
    
            <div id="pills-1">
                <div class="row" style="text-align: center; padding:30px;" id="list1-content1">
                    <p><b>Nothing to be shown!</b></p>
                </div>
            </div>
    
            <div id="pills-2">
                <div class="row content-list" style="text-align:center;" id="list2-content1">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                 class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
        
                        <a href="#" style="display:block;">
                        <div class="col-xs-9 list-content-box" id="div-ht">         
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                        </div>
                        </a>
                </div>
        
                <div class="row content-list" style="text-align:center;" id="list2-content2">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>    
        
                        <a href="#" style="display:block;">
                        <div class="col-xs-9 list-content-box" id="div-ht">         
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                        </div>
                        </a>
                </div>
    
                <div class="row content-list" style="text-align:center;" id="list2-content3">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
            
                        <a href="#" style="display:block;">
                        <div class="col-xs-9 list-content-box" id="div-ht">         
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                        </div>
                        </a>
                </div>
    
                <div class="row content-list" style="text-align:center;" id="list2-content4">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
    
                <div class="row content-list" style="text-align:center;" id="list2-content5">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
    
                <div class="row content-list" style="text-align:center;" id="list2-content6">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>  
        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
    
                <div class="row content-list" style="text-align:center;" id="list2-content7">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                        </div>
                        </a>
                </div>
    
                <div class="row content-list" style="text-align:center;" id="list2-content8">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
            </div>
    
            <div id="pills-3">
                <div class="row content-list" style="text-align:center;" id="list3-content1">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
                        
                <div class="row content-list" style="text-align:center;" id="list3-content2">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                    
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>     
            </div>
    
            <div id="pills-4">
                <div class="row content-list" style="text-align:center;" id="list4-content1">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                            
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>        
            </div>
    
            <div id="pills-5">
                <div class="row content-list" style="text-align:center;" id="list5-content1">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
                    
                <div class="row content-list" style="text-align:center;" id="list5-content2">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                    
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
                
                <div class="row content-list" style="text-align:center;" id="list5-content3">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                    
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
            </div>
    
            <div id="pills-6">
                <div class="row content-list" style="text-align:center;" id="list6-content1">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                    
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
                        
                <div class="row content-list" style="text-align:center;" id="list6-content2">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
                
                <div class="row content-list" style="text-align:center;" id="list6-content3">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>

                <div class="row content-list" style="text-align:center;" id="list6-content4">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
            </div>
    
            <div id="pills-7">
                <div class="row content-list" style="text-align:center;" id="list7-content1">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div> 
                                    
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
                        
                <div class="row content-list" style="text-align:center;" id="list7-content2">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
                
                <div class="row content-list" style="text-align:center;" id="list7-content3">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
            </div>
    
            
            <div id="pills-8">          
                <div class="row content-list" style="text-align:center;" id="list8-content1">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>       
            </div>
    
            <div id="pills-9">
                <div class="row content-list" style="text-align:center;" id="list9-content1">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                    
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
                        
                <div class="row content-list" style="text-align:center;" id="list9-content2">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>       
            </div>   
    
            <div id="pills-10">
                <div class="row content-list" style="text-align:center;" id="list10-content1">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                    
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
                        
                <div class="row content-list" style="text-align:center;" id="list10-content2">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>       

                <div class="row content-list" style="text-align:center;" id="list10-content3">
                        <div class="col-xs-3 list-img" id="div-ht">   
                            <a href="#">
                                <img alt="Brand" src="https://image.freepik.com/free-icon/cartoon-buildings_318-41281.jpg" 
                                class="img-circle" width=60 height=50/>
                            </a>   
                        </div>   
                                        
                        <a href="#" style="display:block;">
                            <div class="col-xs-9 list-content-box" id="div-ht">         
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.</p>              
                            </div>
                        </a>
                </div>
            </div> 
    </div><!--container tab_content-->
    
    <div class="container red" id="tab_details"> 

            <div class="row" id="pill1-content1">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>pill1-content1</b><br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
            
                    <a class="left carousel-control goback1" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>       
            </div>
           
            <div class="row" id="pill2-content1">  
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>pill2-content1</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                           consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                           Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                           consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
    
                    <a class="left carousel-control goback2" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>
            </div>
            
    
            <div class="row" id="pill2-content2">    
                    <div class="col-xs-12" style="padding: 5px;">
                        <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                            <button type="button" class="btn subscribe">Subscribe</button>
                            <p><b>Pills2-content2</b>
                                <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                                consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                                consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            </p>
                        </div>
                
                        <a class="left carousel-control goback2" href="#">
                            <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                        </a>
                    </div>   
            </div>
    
            <div class="row" id="pill2-content3">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills2-content3</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
            
                    <a class="left carousel-control goback2" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div> 
    
            <div class="row" id="pill2-content4">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills2-content4</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
            
                    <a class="left carousel-control goback2" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>
    
            <div class="row" id="pill2-content5">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills2-content5</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
            
                    <a class="left carousel-control goback2" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>
    
            <div class="row" id="pill2-content6">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills2-content6</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
            
                    <a class="left carousel-control goback2" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>   
            
            <div class="row" id="pill2-content7">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills2-content7</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                
                    <a class="left carousel-control goback2" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill2-content8">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills2-content8</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                    
                    <a class="left carousel-control goback2" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill3-content1">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills3-content1</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                        
                    <a class="left carousel-control goback3" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill3-content2">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills3-content2</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                            
                    <a class="left carousel-control goback3" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill4-content1">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills4-content1</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                            
                    <a class="left carousel-control goback4" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill5-content1">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills5-content1</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                
                    <a class="left carousel-control goback5" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill5-content2">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills5-content2</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                    
                    <a class="left carousel-control goback5" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill5-content3">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills5-content3</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                    
                    <a class="left carousel-control goback5" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill6-content1">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills6-content1</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback6" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill6-content2">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills6-content2</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback6" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill6-content3">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills6-content3</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback6" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill6-content4">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills6-content4</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback6" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill7-content1">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills7-content1</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback7" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill7-content2">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills7-content2</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback7" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill7-content3">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills7-content3</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback7" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill8-content1">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills8-content1</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback8" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill9-content1">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills9-content1</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback9" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill9-content2">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills9-content2</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback9" href="#" >
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill10-content1">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills10-content1</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback10" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill10-content2">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills10-content2</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback10" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>

            <div class="row" id="pill10-content3">    
                <div class="col-xs-12" style="padding: 5px;">
                    <div class="col-xs-11 col-xs-offset-1 content-div-inner green">
                        <button type="button" class="btn subscribe">Subscribe</button>
                        <p><b>Pills10-content3</b>
                            <br>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat. Lorem ipsum dolor sit amet, 
                            consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                        </p>
                    </div>
                                        
                    <a class="left carousel-control goback10" href="#">
                        <i class="glyphicon glyphicon-chevron-left" style="color: grey; font-size: 20px;"></i>
                    </a>
                </div>   
            </div>
    </div><!--container-->    

    <div class="container" id="subscription-form">
        <div class="col-xs-12">
            <form>
                Full Name:<br>
                <input type="text" name="firstname">
                <br>
                Email:<br>
                <input type="text" name="lastname">
                <br><br>
                <input type="submit" value="Submit">
            </form>
        </div>
    </div>

    <div class="container red" id="footer-content">
        <div class="col-xs-12">
            <div class="row">
                <div style="background-color:white; padding: 5px 5px 0px 5px;" id="notification-div">
                    <P>
                    <b>Notification</b><br>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.<br>
                    Lorem ipsum dolor sit amet,<br>
                    consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.<br>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.<br>
                    Lorem ipsum dolor sit amet,<br>
                    consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                    </P>
                </div>
            </div>

            <div class="row">
                <div style="background-color:white; padding: 5px 5px 0px 5px;" id="list-div">
                    <P>
                    <b>To-do List</b><br>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.<br>
                    Lorem ipsum dolor sit amet,<br>
                    consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.<br>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.<br>
                    Lorem ipsum dolor sit amet,<br>
                    consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                    </P>
                </div>
            </div>

            <div class="row">
                <div style="background-color:white; padding: 5px 5px 0px 5px;" id="setting-div">
                    <P>
                    <b>Setting</b><br>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.<br>
                    Lorem ipsum dolor sit amet,<br>
                    consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.<br>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.<br>
                    Lorem ipsum dolor sit amet,<br>
                    consectetur adipiscing elit, sed do eiusmod tempor incididunt ut uat.
                    </P>
                </div>
            </div>

        </div>
    </div>
</main>    
    
<footer>
        <div class="container">
            <div class="row text-center">
        
                    <div class="col-3 col-xs-3 col-sm-3 col-md-3 icon-center border-bar" id="home"><a href="#"><i class="glyphicon glyphicon-home"></i>
                            </a></div>
                    <div class="col-3 col-xs-3 col-sm-3 col-md-3 icon-center border-bar" id="notification"><a href="#"><i class="glyphicon glyphicon-bell"></i>
                            </a></div>
                    <div class="col-3 col-xs-3 col-sm-3 col-md-3 icon-center border-bar" id="list"><a href="#"><i class="glyphicon glyphicon-list-alt"></i>
                            </a></div>
                    <div class="col-3 col-xs-3 col-sm-3 col-md-3 icon-center" id="setting"><a href="#"><i class="glyphicon glyphicon-cog"></i>
                            </a></div>
               
            </div>
        </div>
</footer>
    
</body>
</html>                                                           


.red {
    border: 1px solid red;
}

.blue {
    border: 1px solid blue;
}

.green {
    border: 1px solid rgb(41, 117, 34);
}

body {
    background-color: rgb(229, 241, 245); 
}

header{
    position: fixed;
    left: 0px;
    top: 0px;
    right: 0px;
    width: 100%;
    z-index: 100;
    
}

main{
    padding-top: 5px;
    padding-bottom: 0px;    
    margin-top: 136px;
    margin-bottom: 64px;
    z-index: 10;
}

footer{
    position:  fixed;
    left: 0px;
    bottom: 0px;
    right: 0px;
    width: 100%;
    background-color: grey;
    z-index: 100;
}

h1 {
    color: navy; 
    font-size: 17px;
    text-align: center;
    padding-right: 5px;
} 

.hamburger{
    width: 16;
}

#divHeader{
    height: 75px;
    text-align: center;
    padding-top: 20px;
}

.menu ul {
    margin: 0; 
    padding: 0; 
    list-style-type: none; 
    list-style-image: none;
}

.menu li {
    display: block;   
    padding:12px 0 12px 0; 
    border-bottom:#dddddd 1px solid;
}

.menu a{
    text-decoration:none;
}
 
.btn{
    text-align: center;
    background-color: none;
    margin-bottom: 0;
}
  
.border-bar{  
    border-right: 1px solid white;
    text-indent: col-3;
}

i{
    color: white;
    font-size: 18px;
}

a, a:hover, a:focus{
    text-decoration: none;
    color: black;
}

img {
    padding: 5%;
}

#navcol {
    padding-right: 0px;
    padding-left: 0px;
}

button{
    margin-right: 1em;
    border-radius: 50px;
    display: block;
}

.carousel-control.left {
    background-image: none;
}

.carousel-control .glyphicon-chevron-left{
    margin-left: -20px;
}

.carousel-control .glyphicon-chevron-right{
    right: 45%;
    font-size: 20px;
}

.carousel-control{
    width: 14%;
    opacity: 0.9;
    text-shadow: none;
}

.nav-pills > li.active > a, .nav-pills > li.active > a:focus {
    background-color: #eee;
}

#div-ht{
    height: 72px;
}

.content-div{
    float: left;
    overflow: hidden;
    background: white;
}

.content-div-inner{
    padding: 10px;
    background-color: white;
    width: 333px;
}

.content-list{
    padding: 0px 5px 5px;
}

.nav{
    margin-bottom: 12px; 
}

ul{
    margin-top: 12px; 
}

.shift-right{
    text-indent: 10px;
}

.icon-center{
    height: 64px;
    padding: 18px;    
    padding-top: 22px;       
}

.subscribe{
    margin-right: 0px;
    float: right;
    background-color: rgb(167, 152, 167);
    padding: 3px 6px;
}

.list-img{
    text-align: center;
    padding: 10px;
    background-color: white;
}

.list-content-box{
    background-color: lightgrey;
}

#footer-content{
    padding-bottom: 0px;
    padding: 10px 10px 0px 10px;
}


/*
#tab_details{
    overflow: hidden;
    height: 150px;
}

#content2{
    height: 200px;
}

#content-detail{
    top: 136px;
    bottom: 54px;
    background-color: white;
}

h1{
 height: 72px; 
 text-indent: 5px; }

*/
