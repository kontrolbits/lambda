<template>
<q-page>
    <div class="col-12 q-pa-md">
        <q-breadcrumbs style="font-size: 15px">
            <q-breadcrumbs-el label="Index" />
            <q-breadcrumbs-el label="Home" />
        </q-breadcrumbs>
    </div>
    <div class="col-12 q-ml-xs q-mr-md q-col-gutter-md row">
        <div class="col-md-3 col-sm-12 col-xs-12">
            <!-- card1 -->
            <q-card bordered>
                <q-card-section>
                    <div class="row items-center no-wrap">
                        <div class="col q-pl-sm">
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
                </q-card-section>
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
        <div class="col-md-3 col-sm-12 col-xs-12">
            <!-- card2 -->
            <q-card bordered>
                <q-card-section>
                    <div class="row items-center no-wrap">
                        <div class="col q-pl-sm">
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
                </q-card-section>
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
        <div class="col-md-3 col-sm-12 col-xs-12">
            <!-- card3 -->
            <q-card bordered>
                <q-card-section>
                    <div class="row items-center no-wrap">
                        <div class="col q-pl-sm">
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
                </q-card-section>
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
        <div class="col-md-3 col-sm-12 col-xs-12">
            <!-- card4 -->
            <q-card bordered>
                <q-card-section>
                    <div class="row items-center no-wrap">
                        <div class="col q-pl-sm">
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
                </q-card-section>
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
    </div>
    <div class="col-12 q-ma-md">
        <!-- card5 -->
        <q-card bordered>
            <q-card-section>
                <div class="row items-center no-wrap ">
                    <div class="col q-pl-sm ">
                        <div class="text-h6">Our Planet</div>
                        <!-- <div class="text-subtitle2">by John Doe</div> -->
                    </div>
                    <q-space />
                    <div class="col-auto q-pl-sm">
                        <q-btn-toggle class="desktop-only" color="primary" v-model="dataGrafico" toggle-color="secondary" :options="[
                                {label: 'Dia', value: 'dia'},
                                {label: 'Mês', value: 'mes'},
                                {label: 'Ano', value: 'ano'}
                            ]" />
                        <q-btn class="mobile-only" color="grey-7" round flat icon="more_vert">
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
            </q-card-section>
            <q-card-section>
                <img src="../statics/exemplo-grafico.jpg" style="width:100%; height:300px;">
            </q-card-section>

            <q-separator />

            <q-card-actions class="row flex flex-center bg-grey-4">
                <div class="col-md-2 col-sm-6 col-xs-6 flex flex-center ">Resultado 1</div>
                <div class="col-md-2 col-sm-6 col-xs-6 flex flex-center ">Resultado 2</div>
                <div class="col-md-2 col-sm-6 col-xs-6 flex flex-center ">Resultado 3</div>
                <div class="col-md-2 col-sm-6 col-xs-6 flex flex-center ">Resultado 4</div>
                <div class="col-md-2 col-sm-6 col-xs-6 flex flex-center ">Resultado 5</div>
            </q-card-actions>
        </q-card>
    </div>
    <div class="col-12 q-ml-xs q-mr-md q-col-gutter-md row">
        <div class="col-md-3 col-sm-12 col-xs-12">
            <!-- card6 -->
            <q-card bordered>
                <q-card-section>
                    <div class="row items-center no-wrap">
                        <div class="col q-pl-sm">
                            <div class="text-h6">Our Planet</div>
                            <div class="text-subtitle2">by John Doe</div>
                        </div>
                    </div>
                </q-card-section>
                <q-card-section>
                    {{ lorem }}
                </q-card-section>

                <q-separator />

                <q-card-actions class="row flex flex-center">
                    <q-btn class="col-5" flat>Action 1</q-btn>
                    <q-btn class="col-5" flat>Action 2</q-btn>
                </q-card-actions>
            </q-card>
        </div>
        <div class="col-md-3 col-sm-12 col-xs-12">
            <!-- card7 -->
            <q-card bordered>
                <q-card-section>
                    <div class="row items-center no-wrap">
                        <div class="col q-pl-sm">
                            <div class="text-h6">Our Planet</div>
                            <div class="text-subtitle2">by John Doe</div>
                        </div>
                    </div>
                </q-card-section>
                <q-card-section>
                    {{ lorem }}
                </q-card-section>

                <q-separator />

                <q-card-actions class="row flex flex-center">
                    <q-btn class="col-5" flat>Action 1</q-btn>
                    <q-btn class="col-5" flat>Action 2</q-btn>
                </q-card-actions>
            </q-card>
        </div>
        <div class="col-md-3 col-sm-12 col-xs-12">
            <!-- card8 -->
            <q-card bordered>
                <q-card-section>
                    <div class="row items-center no-wrap">
                        <div class="col q-pl-sm">
                            <div class="text-h6">Our Planet</div>
                            <div class="text-subtitle2">by John Doe</div>
                        </div>
                    </div>
                </q-card-section>
                <q-card-section>
                    {{ lorem }}
                </q-card-section>

                <q-separator />

                <q-card-actions class="row flex flex-center">
                    <q-btn class="col-5" flat>Action 1</q-btn>
                    <q-btn class="col-5" flat>Action 2</q-btn>
                </q-card-actions>
            </q-card>
        </div>
        <div class="col-md-3 col-sm-12 col-xs-12 q-mb-sm">
            <!-- card9 -->
            <q-card bordered>
                <q-card-section>
                    <div class="row items-center no-wrap">
                        <div class="col q-pl-sm">
                            <div class="text-h6">Our Planet</div>
                            <div class="text-subtitle2">by John Doe</div>
                        </div>
                    </div>
                </q-card-section>
                <q-card-section>
                    {{ lorem }}
                </q-card-section>

                <q-separator />

                <q-card-actions class="row flex flex-center">
                    <q-btn class="col-5" flat>Action 1</q-btn>
                    <q-btn class="col-5" flat>Action 2</q-btn>
                </q-card-actions>
            </q-card>
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
      lorem: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.',
      dataGrafico: 'dia'
    }
  }
}
</script>
