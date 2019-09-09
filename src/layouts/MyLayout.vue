<template>
<q-layout view="lHh Lpr lFf">
  <!-- DESKTOP -->
  <div class="desktop-only">
    <q-header elevated class="grad">
        <q-toolbar>
            <q-btn flat dense round @click="leftDrawerOpen = !leftDrawerOpen" aria-label="Menu">
                <q-icon name="menu" />
            </q-btn>

                <img src="statics/icons/lambda letra 4.svg" style="width: 161px; height: 32px">

        </q-toolbar>
    </q-header>
        <q-drawer elevated v-model="leftDrawerOpen" content-class="grad-invertido">
        <q-list>
          <div class="q-pa-md text-white" style="max-width: 350px">
                <q-list>
                    <q-expansion-item expand-separator icon="home" label="HOME" default-closeed expand-icon-class="text-white">
                        <q-list padding>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                        </q-list>
                    </q-expansion-item>
                    <q-item clickable v-ripple>
                        <q-item-section avatar>
                            <q-icon name="inbox" />
                        </q-item-section>

                        <q-item-section>
                            INBOX
                        </q-item-section>
                    </q-item>
                    <q-expansion-item expand-separator icon="mail" label="INBOX" default-closeed expand-icon-class="text-white">
                        <q-list padding>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                        </q-list>
                    </q-expansion-item>
                    <q-item clickable v-ripple>
                        <q-item-section avatar>
                            <q-icon name="inbox" />
                        </q-item-section>

                        <q-item-section>
                            INBOX
                        </q-item-section>
                    </q-item>
                    <q-expansion-item expand-separator icon="settings" label="CONFIGURAÇÕES" default-closeed expand-icon-class="text-white">
                        <q-list padding>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                        </q-list>
                    </q-expansion-item>
                    <q-item clickable v-ripple>
                        <q-item-section avatar>
                            <q-icon name="inbox" />
                        </q-item-section>

                        <q-item-section>
                            INBOX
                        </q-item-section>
                    </q-item>
                </q-list>
            </div>
        </q-list>
    </q-drawer>
  </div>
  <!-- MOBILE -->
    <div class="mobile-only">
    <q-header elevated class="grad-mobile">
        <q-toolbar>
            <img src="statics/icons/lambda letra 4.svg" style="width: 161px; height: 32px">
            <q-space/>
            <q-btn flat dense round @click="leftDrawerOpen = !leftDrawerOpen" aria-label="Menu">
                <q-icon name="menu" />
            </q-btn>
            <!-- <div>Quasar v{{ $q.version }}</div> -->
        </q-toolbar>
    </q-header>
        <q-drawer elevated v-model="leftDrawerOpen" content-class="grad-invertido-mobile">
        <q-list>
            <div class="q-pa-md text-white" style="max-width: 350px">
                <q-list>
                    <q-expansion-item expand-separator icon="home" label="HOME" default-closeed expand-icon-class="text-white">
                        <q-list padding>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                        </q-list>
                    </q-expansion-item>
                    <q-item clickable v-ripple>
                        <q-item-section avatar>
                            <q-icon name="inbox" />
                        </q-item-section>

                        <q-item-section>
                            INBOX
                        </q-item-section>
                    </q-item>
                    <q-expansion-item expand-separator icon="mail" label="INBOX" default-closeed expand-icon-class="text-white">
                        <q-list padding>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                        </q-list>
                    </q-expansion-item>
                    <q-item clickable v-ripple>
                        <q-item-section avatar>
                            <q-icon name="inbox" />
                        </q-item-section>

                        <q-item-section>
                            INBOX
                        </q-item-section>
                    </q-item>
                    <q-expansion-item expand-separator icon="settings" label="CONFIGURAÇÕES" default-closeed expand-icon-class="text-white">
                        <q-list padding>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                            <q-item clickable v-ripple>
                                <q-item-section avatar>
                                    <q-icon name="inbox" />
                                </q-item-section>

                                <q-item-section>
                                    Inbox
                                </q-item-section>
                            </q-item>
                        </q-list>
                    </q-expansion-item>
                    <q-item clickable v-ripple>
                        <q-item-section avatar>
                            <q-icon name="inbox" />
                        </q-item-section>

                        <q-item-section>
                            INBOX
                        </q-item-section>
                    </q-item>
                </q-list>
            </div>
        </q-list>
    </q-drawer>
  </div>

    <q-page-container>
        <router-view />
    </q-page-container>
    <div class="desktop-only">
        <q-footer elevated class="footer grad text-white" style="border-radius: 0px">
            <q-toolbar class="flex flex-center">
                <p style="text-align: center">Coporight© <strong> <a> 2019 - Lambda®. </a></strong> Todos os direitos reservados.
                    Desenvolvido por <a href="https://azimutecerto.com.br" style="color:rgba(112, 54, 119, 1) "><strong>Azimute Certo</strong></a></p>
            </q-toolbar>
        </q-footer>
    </div>
    <div class="mobile-only">
        <q-footer elevated class="footer grad-mobile text-white">
            <q-toolbar class="flex flex-center">
                <p style="text-align: center">Coporight© <strong> <a> 2019 - Lambda®. </a></strong> Todos os direitos reservados.
                    Desenvolvido por <a href="https://azimutecerto.com.br" style="color:rgba(112, 54, 119, 1) "><strong>Azimute Certo</strong></a></p>
            </q-toolbar>
        </q-footer>
    </div>
</q-layout>
</template>

<script>
import {
  openURL
} from 'quasar'

export default {
  name: 'MyLayout',
  data () {
    return {
      leftDrawerOpen: false
    }
  },
  methods: {
    openURL
  }
}
</script>

<style>
 .footer {
      position:absolute ;
}

.grad {
    background: linear-gradient(to right, rgba(112, 54, 119, 1) 0%, rgba(241, 121, 27, 1) 100%);
}

.grad-invertido {
    background: linear-gradient(to left, rgba(112, 54, 119, 1) 0%, rgba(241, 121, 27, 1) 100%);
}

.grad-mobile {
    background: linear-gradient(to right, rgba(112, 54, 119, 1) 45%, rgba(241, 121, 27, 1) 100%);
}

.grad-invertido-mobile {
    background: linear-gradient(to left, rgba(112, 54, 119, 1) 10%, rgba(241, 121, 27, 1) 150%);
}

.meu-icone {
    color: rgba(241, 121, 27, 1);
}
</style>
