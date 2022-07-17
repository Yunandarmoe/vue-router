<template>
    <div class="container mt-5">
        <div class="row">
            <div class="col-md-4 mb-4" v-for="i in [1, 2, 3, 4, 5, 6]" :key="i">
                <div class="card">
                    <div class="card-body text-center">
                        <img src="@/assets/logo.png" alt="Product Image">
                        <p class="text-muted fw-bold">Product Name</p>
                        <h5 class="my-3">$ 100</h5>
                        <button class="btn btn-primary w-100">More detail</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>
