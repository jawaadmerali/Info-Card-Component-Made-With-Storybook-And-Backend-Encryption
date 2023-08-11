<template>
    <section class="inline large">
        <div class="grid fixed fixed-max-sm large grid-sm-3">
            <div class="text-center wrap">
                <h2 class="f4 text-bold">Get the most out of your sale with a top local Real Estate agent</h2>
            </div>

            <infoCard
                iconClass="icon-house"
                headerText="Match with a listing agent"
                descriptionText="We’ll connect you to a local agent who will be by your side from listing to closing."
            />
            <infoCard
                iconClass="icon-open-house"
                headerText="Maximize your home sale"
                descriptionText="Your top local Real Estate agent knows the market and can help you identify the right price and the right time to sell."
            />
            <infoCard
                iconClass="icon-user"
                headerText="Accept the right offer"
                descriptionText="When it’s time to close the deal, your agent will assist you in comparing and negotiating offers and contingencies to help you get the best price."
            />
        </div>
    </section>

    <section class="inline large">
        <div class="grid fixed fixed-max-sm large grid-xs-1">
            <div class="text-center">
                <h2><b class="f4 text-bold">Agents you can trust</b></h2>
                <div class="m-t-2">
                    When the time's right, we'll carefully match you with a high-qualified,top local Real Estate agent,who will adapt their expertise and knowledge to your specific circumstance and help guide you through each step of your real estate journey.
                </div>
            </div>
            <div class="agent-tips">
                <ul class="flex text-center ">
                    <li>
                        <i class="icon-hand-care f2"></i>
                        <p>Carefully Vetted </p>
                        <p>Professionals</p>
                    </li>
                    <li>
                        <i class="icon-statistics-report f2"></i>
                        <p>Experienced</p>
                        <p>Negotiators</p>
                    </li>
                    <li>
                        <i class="icon-user-check f2"></i>
                        <p>Local Market</p>
                        <p>Real Estate Experts</p>
                    </li>
                    <li>
                        <i class="icon-shield-star f2"></i>
                        <p>25,000+</p>
                        <p>Experienced Agents</p>
                    </li>

                    <li>
                        <i class="icon-doc f2"></i>
                        <p>3+ Years in</p>
                        <p>the Industry</p>
                    </li>

                    <li>
                        <i class="icon-map-pin-home f2"></i>
                        <p>Nationwide</p>
                        <p>Representation</p>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <section class="inline large">
        <div class="grid center fixed fixed-max-sm grid-xs-1 large">
            <div class="text-center">
                <h2 class="f4 text-bold">Step by step: selling your home</h2>
            </div>
            <div class="agent-workflow-panel">
                <div>
                    <button class="btn small default"><i class="icon-check"></i> Home valuation</button>
                    <div>
                        <div><b class="text-bold">Discover your home’s value</b></div>
                        <div class="f7">See what your home could sell for</div>
                    </div>
                </div>
                <div>
                    <button class="btn small default"><i class="icon-check"></i> Agent matching</button>
                    <div>
                        <div><b class="text-bold">Connect with a market expert</b></div>
                        <div class="f7">Get matched with a local seller’s agent</div>
                    </div>
                </div>
                <div>
                    <button class="btn small default"><i class="icon-check"></i>Listing preparation</button>
                    <div>
                        <div><b class="text-bold">Maximize your home sale</b></div>
                        <div class="f7">Ensure your home is showing ready</div>
                    </div>
                </div>
                <div>
                    <button class="btn small default"><i class="icon-check"></i>Evaluate offers</button>
                    <div>
                        <div><b class="text-bold">Accept the offer that fits</b></div>
                        <div class="f7">Compare offers and contingencies</div>
                    </div>
                </div>
                <div>
                    <button class="btn small default"><i class="icon-check"></i>Closing</button>
                    <div>
                        <div><b class="text-bold"> Complete repairs and close</b></div>
                        <div class="f7">Fix required items and plan to move</div>
                    </div>
                </div>
            </div>
        </div>

    </section>

    <sellHotlead :hotleadOpt="hotleadOpt"></sellHotlead>

</template>

<script src="./sell-card.js"></script>

<style lang="scss">
@import "./sell-card.scss";
</style>
