<script>
	
	import {
		Button,
		Dropdown,
		DropdownItem,
		Chevron,
		DropdownDivider,
		Navbar,
		NavBrand,
		NavHamburger,
		NavUl,
		NavLi
	} from 'flowbite-svelte';
	let group3 = 2;
</script>

<Navbar
	class="max-w-7xl mx-auto my-6 px-4 md:px-6  bg-base-100 rounded-2xl shadow-lg flex justify-between max-w-screen-xl mx-auto bg-gray-900 text-white"
	let:hidden
	let:toggle
>
	<NavBrand href="/">
		<img
			src="NR_Gear_logo_white.png"
			class=" max-w-20 max-h-20 flex items-center space-x-28 py-5"
			alt="Flowbite Logo"
		/>
	</NavBrand>
	<NavHamburger on:click={toggle} />
	<NavUl {hidden} class="ml-3 bg-gray-900 text-white">
		<NavLi href="/" class="cursor-pointer text-gray-500 rounded-2xl ">Home</NavLi>
		<NavLi class="cursor-pointer text-gray-500 rounded-2xl "
			><Chevron aligned>About Us</Chevron></NavLi
		>

		<Dropdown offset="18" class=" bg-gray-800 divide-y ">
			<DropdownItem class="text-gray-500 " href="/about-us">Our team</DropdownItem>
			<!--  <DropdownItem class="text-gray-500">Settings</DropdownItem>
		<DropdownItem class="text-gray-500">Earnings</DropdownItem> -->
			<DropdownItem class="text-gray-500 bg-gray-800 pt-4 " href="https://first.ncresa.org/"
				>Our Parrents Teams! (External Site)</DropdownItem
			>
		</Dropdown>
		<!--<NavLi class="text-gray-500" href="/services">Services</NavLi>
	  <NavLi class="text-gray-500" href="/pricing">Pricing</NavLi>-->
		<NavLi class="text-gray-500" href="/contact-us">Contact</NavLi>
	</NavUl>
	<script src="https://siravijbbpage.statuspage.io/embed/script.js"></script>
</Navbar>
