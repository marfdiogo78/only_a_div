Permitir apenas uma div para ser aberta com a mesma classe

jQuery(document).ready(function($) {

$(".entry-content").hide('slow');

$(".entry-title").click(function() {

    $(".entry-content").hide();
    
$(this).parent().children(".entry-content").slideToggle(500); });

});

Example: http://jsfiddle.net/auUxk/
