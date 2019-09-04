<template>
<q-page class="row">
    <div class="col-12 q-pa-md q-gutter-sm">
        <q-breadcrumbs style="font-size: 15px">
            <q-breadcrumbs-el label="Index" />
            <q-breadcrumbs-el label="Home" />
        </q-breadcrumbs>
    </div>
    <div class="col-12 row">
        <div class="col-3 row">
            <div class="col-12">
                <q-card flat bordered>
                    <q-car-section>
                        <div class="row items-center no-wrap">
                            <div class="col">
                                <div class="text-h6">Our Planet</div>
                                <div class="text-subtitle2">by John Doe</div>
                            </div>
                            <div class="col-auto">
                                <q-btn color="grey-7" round flat icon="more_vert">
                                    <q-menu cover auto-close>
                                        <q-list>
                                            <q-item clickable>
                                                <q-item-section>Remove Card</q-item-section>
                                            </q-item>
                                            <q-item clickable>
                                                <q-item-section>Send Feedback</q-item-section>
                                            </q-item>
                                            <q-item clickable>
                                                <q-item-section>Share</q-item-section>
                                            </q-item>
                                        </q-list>
                                    </q-menu>
                                </q-btn>
                            </div>
                        </div>
                    </q-car-section>
                    <q-card-section>
                        {{ lorem }}
                    </q-card-section>

                    <q-separator />

                    <q-card-actions>
                        <q-btn flat>Action 1</q-btn>
                        <q-btn flat>Action 2</q-btn>
                    </q-card-actions>
                </q-card>
            </div>
            <div class="col-12"></div>
            <div class="col-12"></div>
        </div>
        <div class="col-3">
            <div class="col-12"></div>
            <div class="col-12"></div>
            <div class="col-12"></div>
        </div>
        <div class="col-3">
            <div class="col-12"></div>
            <div class="col-12"></div>
            <div class="col-12"></div>
        </div>
        <div class="col-3">
            <div class="col-12"></div>
            <div class="col-12"></div>
            <div class="col-12"></div>
        </div>
    </div>
    <div class="col-12 row">
        <div class="col-12 row">
            <div class="col-9"></div>
            <div class="col-2"></div>
            <div class="col-1"></div>
        </div>
        <div class="col-12"></div>
        <div class="col-12 row flex flex-center">
            <div class="col-2"></div>
            <div class="col-2"></div>
            <div class="col-2"></div>
            <div class="col-2"></div>
            <div class="col-2"></div>
        </div>
    </div>
    <div class="col-12 row">
        <div class="col-3 row">
            <div class="col-12"></div>
            <div class="col-6"></div>
            <div class="col-6"></div>
        </div>
        <div class="col-3">
            <div class="col-12"></div>
            <div class="col-6"></div>
            <div class="col-6"></div>
        </div>
        <div class="col-3">
            <div class="col-12"></div>
            <div class="col-6"></div>
            <div class="col-6"></div>
        </div>
        <div class="col-3">
            <div class="col-12"></div>
            <div class="col-6"></div>
            <div class="col-6"></div>
        </div>
    </div>
</q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'home',
  data () {
    return {
      lorem: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.'
    }
  }
}
</script>
