<script lang="ts" context="module">
    export type Emoji = {
        apple: string;
        banana: string;
        carrot: string;
        doughnut: string;
        egg: string;
    };

    export type Food = keyof Emoji;
</script>