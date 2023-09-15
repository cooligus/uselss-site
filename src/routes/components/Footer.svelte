<script>
	import './footer.css';
	import Fa from 'svelte-fa';
	import { faRss, faEnvelope } from '@fortawesome/free-solid-svg-icons';
	import { faGithub, faXTwitter } from '@fortawesome/free-brands-svg-icons';
</script>

<footer>
	<div class="icons">
		<Fa size={'1.2em'} icon={faRss} />
		<Fa size={'1.2em'} icon={faEnvelope} />
		<Fa size={'1.2em'} icon={faGithub} />
		<Fa size={'1.2em'} icon={faXTwitter} />
	</div>
	<div>
		<p class="footer-text">© Webpage design name & surname</p>
	</div>
</footer>
