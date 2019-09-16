1. ##### Volha Zbanok
2. Contact Info
    - Phone/Viber: +375297453379
    - Email: olga@zbanok.com
    - GitHub: [https://github.com/olgazbanok](https://github.com/olgazbanok)
	
3. My main goal is to be front-end developer. This job is a good opportunity to realize myself, to grow as a professional. I want to see that my work and my efforts  give results, that they are needed, highly valued and well paid.

4. Python 2/3, Django, JS, HTML, CSS (Bootstrap 4), SQlite, MySQL, Docker, Git.

5. Code example

		function mark(cntr_id){
			$('#' + cntr_id + ' .mark').click(function(){ $(this).toggleClass('marked'); } );
			if ($().tooltip){
				$(document).tooltip({
					track: true,
					items: '.mark.right',
					content: function(){
						var $item = $(this);
						var index = $item.closest('.question').find('.mark.right').index($item);
						var text = $item.closest('.task-body').find('.mark-info').eq(index).html();
						return text;
					}
				});
			}
		}
6. I am involved in the development learning platform for students. ([http://www.elearning.mslu.by](http://www.elearning.mslu.by))

7. BSUIR (Faculty of Computer Systems and Networks). Online course "Introduction to JavaScript and React" on Stepik.org.
