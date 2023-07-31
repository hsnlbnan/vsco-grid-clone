<script>
    import github from '../../lib/images/github.svg';
</script>

<footer class="footer">
    <div class="container mx-auto">
        <div class="
            flex
            flex-col
            md:flex-row
            md:justify-between
            items-center
            mt-8
            border-t-2
            border-gray-200
            pt-8
            md:pt-4
            md:pb-4
        ">
            <p>
                <strong>VSCO Grid Clone </strong> made by <a href="https://linkedin.com/in/husnu">Hüsnü Lübnan</a>.  

            </p>

            <p
                class="
                    text-gray-500
                    text-sm
                    md:text-base
                    mt-2
                    md:mt-0
                    md:order-1
                    md:ml-4
                    flex
                    items-center
                "
            >
                <img src={github} 
                    class="w-6 h-6 inline-block align-middle mr-2"
                alt="Github"/> <a href="https://github.com/hsnlbnan/vsco-grid-clone" target="_blank">hsnlbnan/vsco-grid-clone</a>
            </p>
        </div>
    </div>
</footer>