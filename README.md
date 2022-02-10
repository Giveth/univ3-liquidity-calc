# univ3-liquidity-calc

Some back-of-the envelope calculation for uniV3 liquidity and liquidity ratio calculation.

## Computed values

Let:
- **rL** - liquidity in-range
- **tL** - total liquidity in the pool (all positions)

We find:
- **cR** - concentration ratio 


cR = rL/tL

## Usage

Just run the `calc-liq-ratio.py` script, the output will be printed to stdout.

The script is configured to query the GIV/WETH 0.3% pool on UniV3 at `0xc763b6b3d0f75167db95daa6a0a0d75dd467c4e1`. 

You can pass an alternative pool address as the first parameter.

