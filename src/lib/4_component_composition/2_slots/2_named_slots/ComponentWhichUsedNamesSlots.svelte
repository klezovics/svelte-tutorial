<script>
    import ContactCard from './ContactCard.svelte';
</script>

<ContactCard>
	<span slot="name">
		P. Sherman
	</span>

    <span slot="address">
		42 Wallaby Way<br>
		Sydney
	</span>
</ContactCard>

<ContactCard>
	<div slot="name">
		Arthur K
	</div>

    <div slot="address">
		Riga City. Fun stuff
	</div>
</ContactCard>

