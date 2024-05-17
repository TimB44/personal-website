<script lang="ts">
    export let title: string;
    export let summary: string;
    export let thumbnail: string;
    export let path: string;
</script>
<a href={path}><h2>{title}</h2></a>
<div>
    <p>{summary}</p>
    <img src={thumbnail} alt="thumbnail for {title} project">
</div>

<style>
    div {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }
</style>
