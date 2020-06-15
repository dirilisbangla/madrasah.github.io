/*<script type="text/javascript">*/
		var pre = '';
		$(document).ready(function(){
			$('.selected').hover(function(){
					if($(this).find('.subMenu').css('display')=='none')
					{
						$(this).find('.subMenu').slideDown(600);
						pre = $(this).index() + 1;
					}
				},function(){
					if($('#mainMenu li:nth-child('+pre+') .subMenu').css('display')=='block')
						$('#mainMenu li:nth-child('+pre+') .subMenu').slideUp(600);
			});
		});
	/*</script>*/