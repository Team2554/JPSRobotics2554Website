<!-- If the sponsor should be linked to their website, wrap the SponsorProfile with this component -->

<a href={sponsorWebsiteURL} target="_blank">
    <slot/>
</a>

<script>
    /**
	 * @type {string}
	 */
     export let sponsorWebsiteURL;
</script>