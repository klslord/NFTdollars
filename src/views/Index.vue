<template>
    <div class="container">
        <div class="maintext-container">
            <div style="font-weight: 700;
                        font-size: 120px;
                        line-height: 180px;
                        text-align: center;
                        text-transform: uppercase;
                        color: #FBF8F0;">
                0% INTEREST LOANS
            </div>
            <div style="font-weight: 400;
                        font-size: 30px;
                        line-height: 45px;
                        text-align: center;
                        color: #FBF8F0;">
                Borrow LUSD against ETH
            </div>
        </div>
        <div class="button-container">
            <div><button class="index-button">Borrow Now</button></div>
            <div><button class="index-button">Learn More</button></div>
        </div>
        <div class="total-value-container">
            <div style="font-weight: 700;font-size: 16px;line-height: 100%;text-transform: uppercase;color: #FBF8F0;">
                Total Value Locked
            </div>
            <div style="font-weight: 300;font-size: 40px;line-height: 100%;text-transform: uppercase;color: #FFDD6F;">
                $ 754,692,844
            </div>
        </div>
        <div style="display: flex; flex-direction: column; padding: 80px 288px; gap: 10px; height: 400px;">
            <div class="block-container">
                <div class="index-block">
                    <div class="block-icon-container">
                        <img src="@/assets/index/index_block1_icon.svg">
                    </div>
                    <div class="index-block-inner">
                        <div class="block-title-font">0% Interest Rate</div>
                        <div class="block-text-font">
                            Liquity charges a small, one-time fee to borrow LUSD instead of highly variable interest rates.
                        </div>
                    </div>
                </div>
                <div class="block-divider"></div>
                <div class="index-block">
                    <div class="block-icon-container">
                        <img src="@/assets/index/index_block2_icon.svg">
                    </div>
                    <div class="index-block-inner">
                        <div class="block-title-font">110% Collateral Ratio</div>
                        <div class="block-text-font">
                            Liquity's efficient liquidation mechanism allows users to get the most liquidity for their ETH.
                            *Under normal operation.
                        </div>
                    </div>
                </div>
                <div class="block-divider"></div>
                <div class="index-block">
                    <div class="block-icon-container">
                        <img src="@/assets/index/index_block3_icon.svg">
                    </div>
                    <div class="index-block-inner">
                        <div class="block-title-font">Unstoppable Stablecoin</div>
                        <div class="block-text-font">
                            LUSD is a decentralized stablecoin capable of resisting all kinds of censorship.
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div style="position: absolute; top: 210px; right: 190px;pointer-events: none;">
            <img src="@/assets/index/25_low.png">
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    font-family: 'Poppins';
    font-style: normal;
}

.maintext-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 225px;
}

.button-container {
    display: flex;
    flex-direction: column;
    gap: 16px;
    width: 330px;
    height: 136px;
    margin-top: 45px;
}

.button-container .index-button {
    width: 330px;
    height: 60px;
    border: 2.25px solid #FBF8F0;
    border-radius: 45.75px;
    background-color: transparent;
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 36px;
    text-align: center;
    color: #FBF8F0;
}

.button-container .index-button:hover {
    cursor: pointer;
    background-color: rgba(80, 80, 80, 0.4);
}

.button-container .index-button:active {
    background-color: rgba(4, 4, 4, 0.15);
}

.total-value-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 16px;
    width: 267px;
    height: 72px;
    margin-top: 45px;
}

.block-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 32px;
    width: 864px;
    height: 300px;
}

.block-divider {
    width: 1px;
    height: 300px;
    background: rgba(255, 255, 255, 0.35);
}

.index-block {
    display: flex;
    flex-direction: column;
    gap: 32px;
    width: 245px;
    height: 216px;
}

.block-icon-container {
    width: 48px;
    height: 48px;
    position: relative;
}

.index-block-inner {
    display: flex;
    flex-direction: column;
    gap: 16px;
}

.block-title-font {
    font-weight: 600;
    font-size: 16px;
    line-height: 24px;
    color: #23262F;
}

.block-text-font {
    font-weight: 400;
    font-size: 14px;
    line-height: 24px;
    color: #777E91;
}
</style>