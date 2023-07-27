
<a href={articleURL} class="hover:bg-slate-100" target="_blank">
    <div class="flex flex-col p-5">
        <p class="text-center text-lg font-medium">
            {articleTitle}
        </p>
        <p class="text-center text-sm font-bold">
            {newsSiteName}
        </p>
        <img src={imageURL} class="mx-auto mt-8 max-h-60" alt={imageAlt} />
    </div>
</a>

<script>
    export let articleTitle = "", articleURL = "", newsSiteName = "", imageURL = "", imageAlt = "";
</script>