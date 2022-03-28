# README for combine develepment

0. In addition to all of the node modules, this project requires a global install of docker, ganache.
1. `cp .combine.env .env`
2. `npm build`
3. (in new window) `npm run combine:ganache`
4. (in new window) `npm run deploy ganache`
5. (in new window) `cd docker && docker-compose up`
6. Open `http://localhost:3000` to view app

# Dummy addresses

You can add Ganache as a development chain to Metamask, using the chain ID of `1337`. The accound below each have 100ETH and should do for testing.

Available Accounts
==================

(0) 0x85153aceBC7096972E8f666D104E7539EBaFbC20 (100 ETH)
(1) 0x8b7271671431808a2B0AC12D64Ee900162Cd0788 (100 ETH)
(2) 0x6C41da785296025Cde6BBaaaF4F47eB929694dd5 (100 ETH)
(3) 0x43B47EC1775B15B5144b2d71e5B35cfC20a4e1f0 (100 ETH)
(4) 0xBbdBfd46A1fB2e7D6eDcC42d2a3B5b63345985e7 (100 ETH)
(5) 0x3364B5f2AB35fb0b7c78fd88268011818B6A04F4 (100 ETH)
(6) 0x24038a58513D058F99be09e3a63161c73C17B0B7 (100 ETH)
(7) 0xb2F190017F2154972AE78a40bF936f683E045C86 (100 ETH)
(8) 0xA09A840bdF3279cB35098C89EABE36ebb78f91f1 (100 ETH)
(9) 0x8A06bFCAb15E8Ea458dC0cCE5E78283840A7c37B (100 ETH)

Private Keys
==================
(0) 0xf6023485db3166fa1ac054201c476ebced1c4e111c7acf739d19135f508ce9b3
(1) 0xd1d7bd7d932732f931a7efbebbca3a69b1e1d875c76470bb9c8f7284b216fcfd
(2) 0xcb74a0daa25ce97867694b96755c2d5cb0b0b6de673a0adca712687dc87bfac1
(3) 0xc22fb1f774afad28f3c62ca244dbb0066b7b3d4a07c93a59df73e08c7a89a96c
(4) 0x0b3cc12ffed14c1c0e9525e6b7583e6c7d666e04b78c1d83174beba8da61ed79
(5) 0xf0c39a76af1c23538e6b11682f4fb85e66f2fb3ceeb49cef8720390afbfc3718
(6) 0xdefd74a076a0ed1bd013199470b4865b9d7087c48f1930b222114c11566ee105
(7) 0xacde3fede40b7b7e0cab99741f4b245afdc45677450a305d1c809563ae35ef48
(8) 0x4fea9c6b5fba0b1e3ab7b1e2ae0e9420eb64761f335e26b4cf6f2175d4ff3580
(9) 0xc8452241d61e71173788f92e361ddd782d6c8057d5a9451dacabdd5e276f0949
