<script lang="ts">
    import publications from './publications.json';

</script>

<div class="publications-list">
    <ul class="divide-y divide-gray-200">
        {#each publications as pub}
            <li>
                <a 
                    href={pub.link} 
                    target="_blank" 
                    rel="noopener noreferrer" 
                    class="block p-4 hover:bg-muted transition-all duration-250 ease-in-out"
                >
                    <div class="flex flex-col space-y-1">
                        <h3 class="text-lg font-semibold">
                            {pub.title}
                        </h3>
                        <p class="text-sm">{pub.authors}</p>
                        <p class="text-sm italic">{pub.venue} {pub.year}</p>
                    </div>
                </a>
            </li>
        {/each}
    </ul>
</div>
