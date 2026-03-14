<template>
    <div class="text-center text-4xl font-black font-serif">
        XXX
    </div>
    <div v-if="show_subtext" class="text-center text-2xl font-bold font-serif">
        <div class="h-4"></div>
        How the Story of Oz Came to an End
    </div>
    <div class="h-16"></div>
    <div>
        The writer of these Oz stories has received a little note from Princess Dorothy of Oz which, for a time, has
        made him feel rather disconcerted. The note was written on a broad, white feather from a stork's wing, and it
        said:
    </div>
    <div class="bg-emerald-100/20 p-8 rounded font-black font-serif tracking-wide border-1 border-black/20">
        <div>
            You will never hear anything more about OZ, because we are now cut off forever from all the rest of the world.
            But Toto and I will always love you and all the other children who love us.
        </div>
        <div class="h-8"></div>
        <div>
            <span class="bg-linear-to-t from-emerald-900 to-emerald-200 bg-clip-text text-black/20 text-shadow-xs text-shadow-emerald-200">
                Dorothy Gale
            </span>
        </div>
    </div>
    <div>
        This seemed to me too bad, at first, for Oz is a very interesting fairyland. Still, we have no right to feel
        grieved, for we have had enough of the history of the Land of Oz to fill six story books, and from its quaint
        people and their strange adventures we have been able to learn many useful and amusing things.
    </div>
    <div>
        So good luck to little Dorothy and her companions. May they live long in their invisible country and be very
        happy!
    </div>

</template>

<script setup>

const show_subtext = true

</script>
