<script lang="ts">
	export let image: string
	export let title: string
</script>

<header class="flex flex-row gap-[10px] my-[20px] bg-slate-200">
	<div class="w-full">
		<img src={image} alt={title} class="object-cover h-full"/>
	</div>
    <div class="w-full px-[10px]">
        <slot />
    </div>
</header>
