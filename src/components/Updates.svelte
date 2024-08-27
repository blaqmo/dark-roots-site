<script>
    import Test from "/src/lib/img/test-content.png"
    import Separator from "./Util/Separator.svelte";
</script>

<div id="updates" class="w-full h-screen px-20">
    <div class="pb-20">
        <h1 class="text-5xl pb-2">Updates</h1>
        <p class="text-2xl">Stay informed about the development progress!</p>
    </div>
    <div class="grid grid-cols-3 gap-4 place-items-center">
        <div class="content-box"><img src={Test} alt="test"></div>
        <div class="content-box"><img src={Test} alt="test"></div>
        <div class="content-box"><img src={Test} alt="test"></div>
        <div class="content-box"><img src={Test} alt="test"></div>
        <div class="content-box"><img src={Test} alt="test"></div>
        <div class="content-box"><img src={Test} alt="test"></div>
    </div>
</div>
<Separator />

<style>
    .content-box {
        border: 2px solid #FFF;
    }
</style>