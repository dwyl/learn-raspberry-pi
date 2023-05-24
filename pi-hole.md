![pi-hole-logo-slogan](https://github.com/dwyl/learn-raspberry-pi/assets/194400/aaf1c6fa-48f2-4b6a-a1c1-78d93027dbba)

The purpose of this doc is to document our setup of our `Pi Hole`.

# ⚠️ Disclaimer

We are _not_ `Pi-hole` experts. <br />
We cannot offer `Pi-hole` tech support to anyone. <br />
_However_ if you have followed this guide
and have a _specific_ question, 
please open an issue and we will _attempt_ to help.


# Why?

We decided to run a `Pi-hole` 
because:

1. Privacy - too many tracker in `Chrome`
2. Security - trackers/brokers are leaking our personal data to evil people.
3. `Ads` Waste Time - loading adverts on websites makes them load slower.



# How

Using Raspberry PI Imager (`v1.7.5`), flashing `Raspberry Pi OS (32-bit) to a fresh `SanDisk Ultra MicroSDHC UHS-1 Card`:

![image](https://github.com/dwyl/learn-raspberry-pi/assets/194400/12b93406-3a74-4899-84e6-36729034ae0f)

![image](https://github.com/dwyl/learn-raspberry-pi/assets/194400/59e11730-9db2-4a94-a399-bf5ba9d6a1c5)

![image](https://github.com/dwyl/learn-raspberry-pi/assets/194400/799884d0-df7e-4ab2-8f8e-d05f849bbf92)

![image](https://github.com/dwyl/learn-raspberry-pi/assets/194400/8f10c58f-ffcd-4546-8ce6-9bf16cd6aca3)

While that is writing I'm going to head over to the "networking area" of the workshop
and connect the `Raspberry PI v3 B` (ancient, but apparently more than adequate for `Pi-hole`) 
to the Switch and get everything ready so I can plug-in the `MicroSD` and get started. 

Basically just followed the default instructions at every step.

Configured a static IP Address in the Unifi Console.
Then completed the config with the relevant IP Address.

![image](https://github.com/dwyl/learn-raspberry-pi/assets/194400/78f0d1e3-1584-46cb-8791-d855d8e5e601)

Works a charm.

More detail in the issue: https://github.com/dwyl/learn-raspberry-pi/issues/26#issuecomment-1559660769
