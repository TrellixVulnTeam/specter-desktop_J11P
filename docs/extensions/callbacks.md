
# Callback methods

Callback methods will get called from within Specter Desktop Core for various reasons. You can implement them in your service-class in order to react on those occasions.

Checkout the `cryptoadvance.specter.services.callbacks` file for all the specific callbacks.

Some important one is the `after_serverpy_init_app` which passes a `Scheduler` class which can be used to setup regular tasks. A list of currently implemented callback-methods along with their descriptions are available in [`/src/cryptoadvance/specter/services/callbacks.py`](https://github.com/cryptoadvance/specter-desktop/blob/master/src/cryptoadvance/specter/services/callbacks.py).



