<template>
    <section class="section">
        <div>
            <div class="container">
                <div class="columns has-reverse-row-order-mobile is-height-100">
                    <div class="column">
                        <div class="columns is-centered is-vcentered is-height-100 is-mobile padding-top-4x-mobile">
                            <div class="column is-narrow">
                            </div>
                        </div>
                    </div>
                    <div class="column">
                        <div class="columns is-vcentered is-mobile is-height-100">
                            <div class="column content is-medium fun-text">
                                <h3>{{ $t('fun.title') }}</h3>
                                <p>
                                    {{ $t('fun.description') }}
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss">

    .fun-text {
        @media (min-width: 768px) {
            max-width: 400px;
        }
    }

    .fun-heart {

    }
</style>

<script>



    export default {
        name: 'ob-fun'
    }
</script>

