# Index-ETF-Deconstruction
Calculating Intrinsic Value of Index ETFs and arbitraging inefficiencies

This project gathers the ticker data for every stock in the OEF index

This ticker data is then weighted by market cap and its changes and compared against the OEF price changes

I use interpolation to properly fill in missing OEF values

This is how the project performed using polynomial interpolation

![quadratic_int](https://github.com/Eli-Butters/Index-ETF-Deconstruction/assets/98182401/266bd76c-1db0-43ac-94bf-e35f789169dd)

and this is the performance using linear interpolation

![linear_int](https://github.com/Eli-Butters/Index-ETF-Deconstruction/assets/98182401/bd524974-6eb0-4f48-be81-f3a9b0cbb08a)
