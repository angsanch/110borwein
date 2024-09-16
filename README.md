# 110borwein

Saving years of calculations.

Project for semester 1 of the Epitech Math module.

### Description

This project computes Borwein integrals using numerical methods. It evaluates:

1. The integral `I_n` for a given `n` using:
   - Midpoint rule
   - Trapezoidal rule
   - Simpson's rule

2. The absolute difference between `I_n` and π/2.

The integration interval is from 0 to 5000, divided into 10,000 sub-intervals.

## Getting Started

### Dependencies

- [Python3](https://python.org/)

### Installation

* Download/Clone the repository and enter its directory.
* Now you are ready to run the code.

## Usage

**Execution:** `./110borwein n`

### Arguments
- **`n`**: Constant defining the integral to be computed.

### Examples

To compute the integral for `n = 0`:
```
$> ./110borwein 0
Midpoint:
I0 = 1.5707651076
diff = 0.0000312192
Trapezoidal:
I0 = 1.5707660806
diff = 0.0000302462
Simpson:
I0 = 1.5707654320
diff = 0.0000308948
```

## Acknowledgments

* [Epitech](https://www.epitech.eu/)

## Authors

* **Daniel Sanchez** ([GitHub](https://github.com/angsanch) / [LinkedIn](https://www.linkedin.com/in/angeldanielsanchez/))
* **Xinru Xu** ([GitHub](https://github.com/Exinru) / [LinkedIn](https://www.linkedin.com/in/xinru-xu/))

## License

This project is licensed under the GNU Public License version 3.0 - see the [LICENSE](LICENSE) file for details.
