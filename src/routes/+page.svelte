<script lang="ts">
    import Navbar from './components/navbar.svelte';
    import Publications from './components/publications.svelte';
</script>

<Navbar />

<div class="flex justify-center h-auto">
    <div class="max-w-[40vw] w-full px-4 py-8">
        <div>
            <div class="mb-8 text-lg">
                <p>
                    Gamma Tau is a research group led by Federico Cassano and Noah Shinn with broad interests in AI and programming languages. We host weekly literature reviews and workshops for ongoing work. Check out our past and current projects on GitHub. 
                </p>
                <br/>
                <p>
                    If you are doing interesting work, feel free to reach out to (federico [dot] cassano [at] federico [dot] codes) or (noahrshinn [at] gmail [dot] com). We would love to hear from you. We welcome individuals from all backgrounds.
                </p>
            </div>

            <Publications/>
        </div>
    </div>
</div>