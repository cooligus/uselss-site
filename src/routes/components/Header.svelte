<script>
	import './header.css';
	import Fa from 'svelte-fa';
	import {faSearch, faBars} from '@fortawesome/free-solid-svg-icons';
</script>

<header>
	<nav class="navbar">
		<ul class="navbar-links">
			<li class="main-link">Creative webpage</li>
			<li>Lorem</li>
			<li>Ipsum</li>
			<li>Feugiat</li>
			<li>Tempus</li>
			<li>Adipiscing</li>
		</ul>
		<div class="navbar-icons-cont">
			<div class="navbar-icon-cont">
				<Fa icon={faSearch} size={'1.5em'}/>
			</div>
			<div class="navbar-icon-cont">
				<Fa icon={faBars} size={'1.5em'}/>
			</div >
		</div>
	</nav>
</header>
