# DES F-Function

This Python code implements the F-function of the Data Encryption Standard (DES) algorithm. The F-function is a fundamental component of DES, used for data encryption and decryption. It involves several operations such as expansion, XOR, substitution, and permutation.

## Code Components

- `expansion_box_permutation`: This function expands the input using the expansion box permutation.
- `substitution_boxes`: This function applies the substitution boxes (S-boxes) to the input.
- `permutation_box`: This function permutes the input using the permutation box.
- `des_f_function`: This function performs the complete DES F-function by calling the above functions in the appropriate sequence.

## Usage

1. Run the code and provide the required inputs:
   - Enter the right part of the block (`Ri`) in hexadecimal format.
   - Enter the round key (`Ki`) in hexadecimal format.
2. The code will convert the hexadecimal inputs to binary.
3. The DES F-function will be applied to the inputs.
4. The output after the permutation step will be displayed in hexadecimal format.

## Example

Enter Ri (right part of the block): `1A`
Enter Ki (round key): `23`

Output after permutation step (hex): `D5`

## Note

This code represents a simplified version of the DES F-function for educational purposes. The actual DES algorithm involves additional steps and uses multiple rounds of the F-function for secure data encryption and decryption.
