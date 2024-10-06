<template>
    <BasePage :title="$t('diagramm.DiagrammView')" :isWideScreen="true">
        <div class="row gy-3">
            <div class="page_content_canvas">
                <div
                    class="page_content_layout column_start_start"
                    data-layout="column_start_start"
                    data-id="page_layout_01"
                >
                    <div class="page_content_block fr-view" data-block="rtf" data-id="page_01">
                        <div style="text-align: left">
                            <div class="row row-cols-1 row-cols-md-2 g-1">
                                <div class="card">
                                    <div class="row flex-row-reverse flex-wrap-reverse g-2">
                                        <div>
                                            <div style="text-align: center; color-scheme: inherit">
                                                <desc id="chartinfo1">{{ $t('diagramm.DayData') }}</desc>
                                                <br />

                                                <svg class="chart" aria-label="chartinfo1" width="357" height="130">
                                                    <g class="bar" fill="grey">
                                                        <rect fill="blue" width="10" height="45" y="55" x="0" />
                                                        <text
                                                            x="57"
                                                            y="102"
                                                            data-bs-theme="dark"
                                                            style="
                                                                -moz-transform: rotate(30deg);
                                                                -ms-transform: rotate(30deg);
                                                                -o-transform: rotate(30deg);
                                                                -webkit-transform: rotate(30deg);
                                                                transform: rotate(30deg);
                                                            "
                                                        >
                                                            0
                                                        </text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect
                                                            :fill="$t(setcol())"
                                                            width="10"
                                                            height="45"
                                                            y="55"
                                                            x="15"
                                                        />
                                                        <text
                                                            fill="black"
                                                            x="69"
                                                            y="95"
                                                            style="transform: rotate(030deg)"
                                                        >
                                                            1
                                                        </text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect
                                                            fill="basepage.filler"
                                                            width="10"
                                                            height="80"
                                                            y="20"
                                                            x="30"
                                                        />
                                                        <text x="81" y="88" style="transform: rotate(030deg)">2</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="15" y="85" x="45" />
                                                        <text x="93" y="81" style="transform: rotate(030deg)">3</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="16" y="84" x="60" />
                                                        <text x="109" y="74" style="transform: rotate(030deg)">4</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="100" y="0" x="75" />
                                                        <text x="122" y="67" style="transform: rotate(030deg)">5</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="45" y="55" x="90" />
                                                        <text x="135" y="60" style="transform: rotate(030deg)">6</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="80" y="20" x="105" />
                                                        <text x="148" y="53" style="transform: rotate(030deg)">7</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="15" y="85" x="120" />
                                                        <text x="161" y="46" style="transform: rotate(030deg)">8</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="16" y="84" x="135" />
                                                        <text x="174" y="39" style="transform: rotate(030deg)">9</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="100" y="0" x="150" />
                                                        <text x="187" y="32" style="transform: rotate(030deg)">10</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="45" y="55" x="165" />
                                                        <text x="200" y="25" style="transform: rotate(030deg)">11</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="80" y="20" x="180" />
                                                        <text x="213" y="18" style="transform: rotate(030deg)">12</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="15" y="85" x="195" />
                                                        <text x="226" y="11" style="transform: rotate(030deg)">13</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="16" y="84" x="210" />
                                                        <text x="239" y="4" style="transform: rotate(030deg)">14</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="100" y="0" x="225" />
                                                        <text x="252" y="-3" style="transform: rotate(030deg)">15</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="45" y="55" x="240" />
                                                        <text x="240" y="120">16</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="80" y="20" x="255" />
                                                        <text x="255" y="120">17</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="15" y="85" x="270" />
                                                        <text x="270" y="120">18</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="16" y="84" x="285" />
                                                        <text x="285" y="120">19</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="100" y="0" x="300" />
                                                        <text x="300" y="120">20</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="45" y="55" x="315" />
                                                        <text x="315" y="120">21</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="80" y="20" x="330" />
                                                        <text x="330" y="120">22</text>
                                                    </g>
                                                    <g class="bar">
                                                        <rect fill="blue" width="10" height="15" y="85" x="345" />
                                                        <text x="345" y="120">23</text>
                                                    </g>
                                                </svg>
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <div class="col-10">
                                    <div class="card" style="overflow: hidden">
                                        <div style="text-align: center">
                                            <div class="card-header">{{ $t('diagramm.WeekData') }}</div>
                                            <div class="card-body card-text text-center">
                                                <div class="table-responsive">
                                                    <svg class="chart" width="205" height="125">
                                                        <g class="bar">
                                                            <rect width="25" height="45" y="55" x="0" />
                                                            <text x="0" y="120">Mo</text>
                                                        </g>
                                                        <g class="bar">
                                                            <rect width="25" height="80" y="20" x="30" />
                                                            <text x="30" y="120">Die</text>
                                                        </g>
                                                        <g class="bar">
                                                            <rect width="25" height="15" y="85" x="60" />
                                                            <text x="60" y="120">Mi</text>
                                                        </g>
                                                        <g class="bar">
                                                            <rect width="25" height="16" y="84" x="90" />
                                                            <text x="90" y="120">Do</text>
                                                        </g>
                                                        <g class="bar">
                                                            <rect width="25" height="100" y="0" x="120" />
                                                            <text x="120" y="120">Fr</text>
                                                        </g>
                                                        <g class="bar">
                                                            <rect width="25" height="100" y="0" x="150" />
                                                            <text x="150" y="120">Sa</text>
                                                        </g>
                                                        <g class="bar">
                                                            <rect width="25" height="90" y="10" x="180" />
                                                            <text x="180" y="120">So</text>
                                                        </g>
                                                    </svg>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <div class="card">
                                    <div class="row flex-row-reverse flex-wrap-reverse g-2">
                                        <div style="text-align: center">
                                            <desc id="chartinfo1">{{ $t('diagramm.MonthData') }}</desc>
                                            <br />
                                            <svg class="chart" aria-label="chartinfo1" width="150" height="130">
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="45" y="55" x="0" />
                                                    <text x="0" y="120">1</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="80" y="20" x="10" />
                                                    <text x="10" y="120">2</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="15" y="85" x="20" />
                                                    <text x="20" y="120">3</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="16" y="84" x="30" />
                                                    <text x="30" y="120">4</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="100" y="0" x="40" />
                                                    <text x="40" y="120">5</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="45" y="55" x="50" />
                                                    <text x="50" y="120">6</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="80" y="20" x="60" />
                                                    <text x="60" y="120">7</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="15" y="85" x="70" />
                                                    <text x="70" y="120">8</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="16" y="84" x="80" />
                                                    <text x="90" y="120">9</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="100" y="0" x="90" />
                                                    <text x="90" y="120">10</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="45" y="55" x="0" />
                                                    <text x="0" y="120">11</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="80" y="20" x="10" />
                                                    <text x="10" y="120">12</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="15" y="85" x="20" />
                                                    <text x="20" y="120">13</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="16" y="84" x="30" />
                                                    <text x="30" y="120">14</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="100" y="0" x="40" />
                                                    <text x="40" y="120">15</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="45" y="55" x="50" />
                                                    <text x="50" y="120">16</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="80" y="20" x="60" />
                                                    <text x="60" y="120">17</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="15" y="85" x="70" />
                                                    <text x="70" y="120">18</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="16" y="84" x="80" />
                                                    <text x="90" y="120">19</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="100" y="0" x="90" />
                                                    <text x="90" y="120">20</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="45" y="55" x="0" />
                                                    <text x="0" y="120">21</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="80" y="20" x="10" />
                                                    <text x="10" y="120">22</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="15" y="85" x="20" />
                                                    <text x="20" y="120">23</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="16" y="84" x="30" />
                                                    <text x="30" y="120">24</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="100" y="0" x="40" />
                                                    <text x="40" y="120">25</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="45" y="55" x="50" />
                                                    <text x="50" y="120">26</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="80" y="20" x="60" />
                                                    <text x="60" y="120">27</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="15" y="85" x="70" />
                                                    <text x="70" y="120">28</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="16" y="84" x="80" />
                                                    <text x="90" y="120">29</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="100" y="0" x="90" />
                                                    <text x="90" y="120">30</text>
                                                </g>
                                                <g class="bar">
                                                    <rect fill="blue" width="5" height="100" y="0" x="90" />
                                                    <text x="90" y="120">31</text>
                                                </g>
                                            </svg>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </BasePage>
</template>

<script lang="ts">
import BasePage from '@/components/BasePage.vue';

import { authHeader, authUrl, handleResponse, isLoggedIn } from '@/utils/authentication';
import { defineComponent } from 'vue';

export default defineComponent({
    components: {
        BasePage,
    },
    data() {
        return {
            socket: {} as WebSocket,
            isWebsocketConnected: false,
        };
    },

    methods: {
        setcol() {
            return 'red';
        },

        isLoggedIn,
        getInitialData() {
            fetch('/api/livedata/status', { headers: authHeader() }).then((response) =>
                handleResponse(response, this.$emitter, this.$router)
            );
        },

        initSocket() {
            console.log('Starting connection to WebSocket Server');

            const { protocol, host } = location;
            const authString = authUrl();
            const webSocketUrl = `${protocol === 'https:' ? 'wss' : 'ws'}://${authString}${host}/livedata`;

            this.socket = new WebSocket(webSocketUrl);
        },
    },
});
</script>

<style>
.btn-group {
    border-radius: var(--bs-border-radius);
    margin-top: 0.25rem;
}
</style>
