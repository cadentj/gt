<script lang="ts">
    import { onMount } from 'svelte';

    export let text: string = 'Lorem ipsum dummy text blabla.';
    export let speed: number = 200;

    let displayText: string = '';
    let i: number = 0;

    function typeWriter() {
        if (i < text.length) {
            displayText += text.charAt(i);
            i++;
            setTimeout(typeWriter, speed);
        }
    }

    onMount(() => {
        typeWriter();
    });
</script>

<h1 class="text-2xl font-bold">{displayText}</h1>