# pixi-gnuradio
 A configuration for running Gnuradio through pixi

 With pixi a custom conda environment can be created on the fly

 To run:

     pixi run gnuradio-companion

To add a dependency:

    pixi add plotly

To get a shell for running commands ("activate")

   pixi shell
   

One can instead use global install

     pixi global install --environment gnuradio --expose gnuradio-companion gnuradio gnuradio-grc gnuradio-satellites gnuradio-qtgui gnuradio-zeromq

If installed globally, it can be run with

    gnuradio-companion


See pixi for more features.
