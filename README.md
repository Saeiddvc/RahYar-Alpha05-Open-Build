# RahYar Alpha05 Open Build

## Current status

The earlier `RahYar-alpha05-open-arm64` artifact produced by the Organic Maps wrapper workflow is **REJECTED — DO NOT USE**. It built the Organic Maps application UI with RahYar branding and is not the RahYar product.

The active workflow now builds only from the real private `Saeiddvc/SaeidNavigator-Android` source and verifies:

- package `ir.rahyar.app`
- launcher `ir.rahyar.app.RahYarV3Activity`
- RahYar Persian map-first UI
- MapLibre/open-provider stack
- no Google Navigation SDK
- no Organic Maps application code/UI

The corrected workflow is manual-only and requires the repository secret `RAHYAR_SOURCE_TOKEN` with read-only access to `Saeiddvc/SaeidNavigator-Android`.
