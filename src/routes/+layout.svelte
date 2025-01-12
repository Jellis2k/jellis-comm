<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<!-- Navigation -->
 <!-- border-2 border-[#fc6e83] -->
<nav class="fixed top-8 left-1/2 transform -translate-x-1/2 sm:text-2xl text-lg p-4 bg-black bg-opacity-50 backdrop-blur-lg rounded-full ">
	<a href="/" class="text-[#fc6e83] transition-colors duration-50 hover:text-[#e6d5d3]">Home</a>
	<span>|</span>
	<a href="/commissions" class="text-[#fc6e83] transition-colors duration-50 hover:text-[#e6d5d3]">Commissions</a>
	<!-- <span>|</span>
	<a href="/portfolio" class="text-[#fc6e83] transition-colors duration-50 hover:text-[#e6d5d3]">Portfolio</a> -->
</nav>


{@render children()}

<!-- Footer -->
<footer class="text-center py-4 mt-4 bg-black bg-opacity-20">
  	© 2025 Jellis. 
	<span class="text-[#e6d5d37a]">Last edited: January 12th 2025</span>
	<!-- add about this website? -->
</footer>