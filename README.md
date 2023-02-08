# AES Implementation in Python
### Author: Hamza Khalid

## How to run the code
You can run the code through the terminal by using the following command:

```
python aes.py -c <command> -k <key> -i <input file> -m <mode> -o <output file>
```

For Help
```
python aes.py -h
```

## Commands
The following commands are available:

- **encrypt**: Encrypts the plaintext using the key
- **decrypt**: Decrypts the ciphertext using the key
- **keygen**: Generates a key of the specified size
- **mode**: Specifies the mode of operation

## Modes of Operation
The following modes of operation are available:

- **ecb**: Electronic Code Book
- **cbc**: Cipher Block Chaining

## Key Size
The following key sizes are available:

- **128**: 128 bit key
- **192**: 192 bit key
- **256**: 256 bit key

## Examples
### Encrypting a file
```
python aes.py -c e -k key.key -i plaintext.pt -m ECB -o ciphertext.enc
```

### Decrypting a file
```
python aes.py -c d -k key.key -i ciphertext.enc -m ECB
```

### Generating a key
```
python aes.py -c g -s 128
```

# Encyption Speed
Throughput:  0.025991468768354727 MB/sec

# Decryption Speed
Throughput:  0.026324802180452318 MB/sec

# Features

- **ECB**: Electronic Code Book mode of operation
- **CBC**: Cipher Block Chaining mode of operation
- **keygen**: Generates a key of the specified size
- **mode**: Specifies the mode of operation
- **key**: Specifies the key to be used
