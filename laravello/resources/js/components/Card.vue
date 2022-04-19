<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Board Component</div>

                    <div class="card-body">
                       <h2>This is Board {{counter}} </h2>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                counter: 100
            }
        }
    }
</script>
