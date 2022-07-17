<script>
    export let icon;
    export let text = "tooltip L";
    import Icon from "svelte-icons-pack/Icon.svelte";
</script>

<div class="sidebar-icon group">
    <Icon src={icon} />
    <span class="sidebar-tooltip group-hover:scale-100">
        {text}
    </span>
</div>
