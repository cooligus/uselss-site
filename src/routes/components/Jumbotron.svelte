<script>
	import Button from './Button.svelte';
	import './jumbotron.css';
	import Fa from 'svelte-fa';
	import {faHeart, faComment} from '@fortawesome/free-solid-svg-icons';
</script>

<article class="jumbotron">
	<header class="inline-header">
		<div class="left-heading">
			<h2 class="jumbotron-h2">Magna sed adipiscing</h2>
			<h3 class="jumbotron-h3">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h3>
		</div>
		<div class="right-heading">
			<time class="jumbotron-time">November 4, 2023</time>
			<div class="jumbotron-person">
				<p>Jane doe</p>
			<img src="https://baconmockup.com/64/64" alt="" class="avatar" />
			</div>
		</div>
	</header>
	<section class="jumbotron-content">
		<img src="https://baconmockup.com/1000/600" alt="" />
		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam recusandae nobis molestias
			tempore aliquid perferendis officia porro atque suscipit? Modi soluta molestiae quia ut nulla.
			Officia vitae nobis earum esse. Lorem ipsum dolor sit amet consectetur adipisicing elit.
			Deleniti tenetur voluptas, ducimus facilis, aut accusamus dolor illum ipsa odio blanditiis
			vitae maiores, placeat quaerat veniam provident in cumque reprehenderit! Reiciendis!
			Repellendus dolor impedit quas quod delectus sed corporis ea animi sint obcaecati perspiciatis
			repellat eius corrupti ut ad, fuga cupiditate ex nemo iste labore, officia cum consequatur
			incidunt. Incidunt, impedit! Aspernatur cumque exercitationem adipisci ullam consectetur enim
			dolore nulla. Sunt illo ad ea porro, architecto pariatur adipisci omnis amet repudiandae
			dignissimos dolorem? Voluptates esse voluptatibus sed autem magni. Accusamus, blanditiis!
		</p>
	</section>
		<section class="jumbotron-subcontent">
		<div class="jumbotron-button-cont">
			<Button>Continue reading</Button>
		</div>
		<div class="jumbotron-social-cont">
			<p class="general-link space-border-right">General</p>
			<p class="space-border-right"><Fa icon={faHeart}/> z 8</p>
			<p><Fa icon={faComment}/> 1 z 8</p>
		</div>
	</section>
</article>
