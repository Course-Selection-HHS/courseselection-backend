<template>
    <div id="hamburger">
        <svg 
            xmlns="http://www.w3.org/2000/svg" 
            xmlns:xlink="http://www.w3.org/1999/xlink" 
            height="32px" 
            id="Layer_1" 
            style="enable-background:new 0 0 32 32;" 
            version="1.1" 
            viewBox="0 0 32 32" 
            width="32px" 
            xml:space="preserve">
            <path d="M4,10h24c1.104,0,2-0.896,2-2s-0.896-2-2-2H4C2.896,6,2,6.896,2,8S2.896,10,4,10z M28,14H4c-1.104,0-2,0.896-2,2  s0.896,2,2,2h24c1.104,0,2-0.896,2-2S29.104,14,28,14z M28,22H4c-1.104,0-2,0.896-2,2s0.896,2,2,2h24c1.104,0,2-0.896,2-2  S29.104,22,28,22z"/>
        </svg>
    </div>
</template>

<script> 
export default {
  name: 'Hamburger'
}
</script>

<style lang="scss" scoped>
    svg {
        fill: var(--red2);
        transition: all .25s;
        user-select: none;

        &:hover {
            transform: scale(1.25);
            fill: var(--red3);
        }
        &:active {
            transform: scale(.75);
        }
    }
</style>