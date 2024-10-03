<script lang="ts">
    import Logo from "./gammatau.svg";
</script>

<nav class="w-full pt-2">
    <div class="max-w-[40vw] mx-auto px-4 py-2">
        <div class="flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <img src={Logo} alt="Gamma Tau" class="w-12 h-12" />
                <h1 class="text-2xl font-bold">Gamma Tau</h1>
            </div>
            <button class="join-button">Get Involved</button>
        </div>
    </div>
</nav>

<style>
    .join-button {
        @apply rounded text-primary-foreground bg-primary px-4 py-2 hover:bg-primary/90;
    }
</style>