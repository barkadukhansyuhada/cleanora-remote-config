# Cleanora remote configuration

This public repository contains non-secret runtime configuration consumed by Cleanora.

- Edit `ads-config.properties` to update the ad mode, independently enable the Home banner or Home-to-Heavy-Apps interstitial, set the 60–3600 second interstitial cooldown, and provide public AdMob identifiers.
- Never commit passwords, tokens, signing files, or private identifiers.
- The Android client validates every field and fails closed when production configuration is invalid.

Implementation and activation rules live in the private Cleanora application repository.
