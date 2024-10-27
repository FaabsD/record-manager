<template>
    <div class="bg-gray-50 dark:bg-neutral-900 min-h-screen">
        <SiteNav/>
        <div class="prose max-w-none lg:max-w-screen-xl mx-auto my-2 lg:my-4 dark:prose-zinc dark:prose-headings:text-zinc-50">
            <slot name="content"/>
        </div>
    </div>
</template>