# Chain Reaction

Provides a temporary workaround to https://gitlab.com/foundrynet/foundryvtt/-/issues/6417 , allowing rolls such as 1d20x10x20 to work as expected.

Should still work once that bug is fixed, but will be unnecessary at that point.

Multiple xo modifiers are handled seperately - e.g. 1d20xo10xo20 will explode once on a 10 AND once on a 20, if both are rolled.

# License

Almost all the the code in this is from Foundry, used under the limited license for module development https://foundryvtt.com/article/license/

Any changes I have made are free to use, adapt, whatever you want, with no implied warranties of any kind, but for use outside of what is permitted by the Limited License for Module Development you must do your own due diligence to ensure that you are not duplicting Foundry's code.
