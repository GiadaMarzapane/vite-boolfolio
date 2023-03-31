<!--
    Per passare da Composition API a Options API dobbiamo:
    1. Rimuovere l'attributo setup da <script>
    2. Aggiungere l'export default {}
    3. Aggiungere la proprietà name nell'oggetto esportato che avrà come valore il nome del componente (opzionale, ma buona pratica)
-->
<script>
export default {
    name: "HelloWorld",
    data() {
        return {
        };
    },
    
};
</script>

<<template>

</template>>

<style scoped>
</style>
