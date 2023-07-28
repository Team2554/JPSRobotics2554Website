<!-- Shown in sidebar on homepage -->

<a href={sponsorWebsiteURL} target="_blank">
    <div class="max-w-4xl mx-auto bg-slate-50 hover:bg-slate-100">
        <img src={sponsorImgURL} class="mx-auto" width={sponsorImgWidth} alt="{sponsorName} Logo"/>
    </div>
</a>

<script>
    export let sponsorName = "", sponsorImgURL = "", sponsorImgWidth = '50%';

    /**
     * @type {string}
    */
    export let sponsorWebsiteURL;
</script>