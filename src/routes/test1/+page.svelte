<script>
	
	function handleAnchorClick (event) {
		event.preventDefault()
		const link = event.currentTarget
		const anchorId = new URL(link.href).hash.replace('#', '')
		const anchor = document.getElementById(anchorId)
		window.scrollTo({
			top: anchor.offsetTop,
			behavior: 'smooth'
		})
	}

</script>


<a class= 'balls' href="#facebook_ads_example">
	balls
</a>

<p>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br></p>


<h2 class = 'balls'id="facebook_ads_example">real</h2>
<p>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br>t<br></p>

<style>

    p {
        font-size: 100px;
    }

    .balls {
        scroll-behavior: smooth;
        transition: all .4s ease;
    }
</style>
