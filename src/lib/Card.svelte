<script>
    let { Icon, textColor, borderColor, heading, text } = $props();
</script>

<div
    class="bg-white rounded-xl p-6 border {borderColor} "
>
    <Icon class="h-8 w-8 {textColor} mb-4 absolute" />
    <h3 class="text-xl font-semibold text-gray-900 mb-3 mx-auto wrap-normal px-10">
        {heading}
    </h3>
    
    <p class="text-gray-600">
        {text}
    </p>
</div>
