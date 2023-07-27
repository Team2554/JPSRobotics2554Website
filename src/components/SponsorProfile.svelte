
<div class="max-w-4xl mx-auto mt-14 bg-slate-50 hover:bg-slate-100 p-5">
	<img src={sponsorImgURL} class="mx-auto mt-8" width={sponsorImgWidth} alt="{sponsorName} Logo"/>
    {#if sponsorBlurb}
    <p class="text-center pt-5">{sponsorBlurb}</p>
    {/if}
</div>

<script>
    export let sponsorName = "", sponsorBlurb = "", sponsorImgURL = "", sponsorImgWidth = '60%';
</script>