---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠== You can decompress Drawing data with the command palette: 'Decompress current Excalidraw file'. For more info check in plugin settings under 'Saving'


# Excalidraw Data
## Text Elements
tokens = ["1","2","+","3","*","4","-"] ^i5jBWneH

Output: 5 ^yUJxXpD7

> push 1 [1]
> push 2 [1, 2]
> operand so pop last two and do
operation
> 1 + 2 = 3
> push result to stack [3]
> push 3 to stack [3, 3]
> operand so pop last two numbers and 
do operation
> 3 * 3 = 9
> push result to stack [9]
> push 4 to the stack [9, 4]
> operand so pop last two and do operation
> 9 - 4 = 5
> push 5 to the stack [5]
> input tokens has reached the end
so return result value ^9tou9beC

conditions
- when we see an operand pop the last two
values and perform operation
- once done performing operation push back to
result stack
- continue until we've reached the end of the
input stack ^dLDsbPBk

%%
## Drawing
```compressed-json
N4KAkARALgngDgUwgLgAQQQDwMYEMA2AlgCYBOuA7hADTgQBuCpAzoQPYB2KqATLZMzYBXUtiRoIACyhQ4zZAHoFAc0JRJQgEYA6bGwC2CgF7N6hbEcK4OCtptbErHALRY8RMpWdx8Q1TdIEfARcZgRmBShcZQUebQA2bQB2GjoghH0EDihmbgBtcDBQMBKIEm4ygFYAKwAhAHUOBAAJVJLIWEQKqCwoNtLMbmceeIBGBIAWJIBOaYBmCbmeUYAG

eKT+Upghnkrxifj46ZXKlaSeGdH4uc3IChJ1bkPxlbmADiTKpKWJ5be325SBCEZTSbiVObJSoTUZvObxN5nObTCbTQHWZTBbgrQHMKCkNgAawQAGE2Pg2KQKgBiUbTJKjbA8fqQTS4bCE5QEoQcYhkilUiT46zMOC4QLZFkQABmhHw+AAyrAsRJBB4pXiCcT6g9JNw+IUBPiiQglTAVeg1eVAdzQU1mLk0KNAWwxdg1NsnSscYaIFzhHAAJLER2o

ArtSAAKTg+gAYkliHMAGoAGQAImxY65SM45tV6AAFKmGgC6gOl5Eywe4HCE8sBhF5WAquBWUu5vPtodr9d9YQQxG45yuJ2RN19jBY7C4TqugMnrE4ADlOGJuKNPhMDnM5pUG8w0+keoO0NKCGFAZphLyAKLBTLZbt1/CAoRwYi4Y/r75jt7HC7xHuvpEBwhI1s+gIUhyA7cGe+AXr6PSYH0QomhwzCoAAvGGAA6ECjHh1B4TwhF4QA1KREBzJRAB

UlETJRzh4SW7aUAAKr03RoRh2F5HhBE0MRlEUYJVG0fRjHMVK0qcFACqEEY4ioIs2jejuBwohMlTTKM2nlrJsa4PocqeqgQHtNAvQAIJEMoM7oME0p9POTBQOYBA2SC9nQK6Up6NkuCNkw1ZoD2L6+pSIKNgQHHIVxxLoVhuH4ZRJGiSJRFiaJdGiQxolMRALHokIUBsAASuEClKfiQgIJBQXNMCoIoag4y7IUAC+mzFKU5QSDAACqkaYAAGnAaY

pICnRKZZcWAoMaAHEk2iVEcoxzEihzxCszq+qZwxTNo9Lwq8vxJDCO3jhZ9zEI8TrzAk52rScBwfOZpSSE1YJoKcK3XBu8J7EclQjOiHCYkpPoWZqJr8pSNJ0gyTJSmyHL+jyfLkvDQrkOhYoSs5vqyvKZoWhAVqDrixrarq+pU1qprKjNFPtsIdrhKGu0Wa67Ieuu3qAujQYhvkhpRjG8aJqmGZZkwub5kWECluWlYICFqBhQ2TYLeguCjKzGNd

uBvbQwgMFoGMPAot8ekTkwi72bpAJ21Oy6rkpoxbjwO0XMs+6HsEX6nuedW+leGN3hkWQ5Mb4UWW+H5B61P7zH+KwAe9kAgWBoUQcBbDQSeqBwQhFlIS1EAAPIlXAJU/axFCxRX1eyHXZnSbJ8mKdwEwrNoWmjn+yy7vE3uZzKBlGSZ4JTdZtneY5hMWZObnuJ5dlcXAfmyYFTSkOrmsRaQUUcDFnESC3tdQPXxWlRVrDd2gNWhxZIEtF9LVtZUn

Xdb6fXoNMUqQhpiaFJFKaa3ROLzR2NcZIRw/znW2vMT4gJ9qezeP3JEsJRi6R4Asd4gIbp3VQKPDBDI3iHEqNpaYbw8GAk+iCb6qA3hULBhDbE9NYZY0FOgWk9JGTMkvOyTkHZMYCm6LjUU4po7STlIqJmFQWacJprdPUaADTQ2pozc0zNyTWl9LaSQRsnQujdHzL0UNShC2DKGcMFloxxgTMmdMmZszy0LMWdoZYiaqwPnnCyjZiDNgkLgQRBjr

zEGMRrfxpR+xFw3HsOYODXguVdvZWYGwXYOxXBwNcFiWHnCSOsf2R5zbFxDpeCJkcHwx1zibUoCdPxlIBr+f8RTx7Z1jpBAuxIi4lxfqUcuFQAB8qBa7MEkK1MMowSw4Q4KM8ZkyeDTOoLwWZ8zUCuiYNYYgqBBBjNdKgfAoQoCoCgBQNgqAdmoGIGwOZWzyBuU4HM0ZoxUBkV4ElaiGzFmoECMwOspzSp7KiByMMcx1kLKEBM1AcwzmXLxMI8Fq

yIUvM2YgXGuz9lwEOccvEZyLnRP0KAlgczrlzNuei7ZTyOBorhTRWFSVphot+f8wF8KQVIryNMSFYzoWTImBy9QCBOVgu5asiYvKHnXOxbik5BLLnXNufcjFn5pxoumKgZwykkqVBZfysyQrPqisJGGSovLGxX3hQlDCkhQh/JCNgT6uzhWoCyMQOZ+zAhQBEBwB1AL8CnPoAQWqDcm4jL5TCt5eQZn6phcsmNqyeBStVbyPZlycVwCOfK85iq03

Ko4NKmlaK3kfOWdhb5UKYVssDRyxFYrUU/INXC4F9bTV5BuLClN2y02yqzXioFhLazEvtlctNFLLlFvVRs+ljLsLMqbdW8I7LW2gvbTyuNAqjUirbWGNEylu2YvTQc/tObCVKsnaq4tGzNXasFdhPVi7JmVG3Sas1FqOBWtKja1AdqMKBHZM6s5xr3Wesud631/r2XBt8EgfS2Qu5KXhPBqAhljL4FMuPcu68F4ICclKFe7l8A4c3tvAKQV95F0P

tzY+/gz5xQkFWyZ0bY1Ps+YmtZaLpW9ozXK/Fuax27ILVO55GzS2fIrZuqDtbV1csbUxxlsmG0osPTK3jp7+NDqECOlggnUATqpY86dozZ1wvnVJmtQKEVrr3by35grgWut3eKg9XHU1YvU9mzTeahOXupcZ1At6dUPqky+xzxrnPmrRZakq1qsi2vtQBp1A5gMitA+hcDCAfWkD9ZZ1AMHQ233KpVR+5T4IDKzg1D+65tDtRKF1QoPVID/wgMQd

MzBNAFlqGBKa8AZpDOgWgZE4wcHrDhHCVaDINFbCGKsOIrwKHrCdvEKYaxCG00Wv8VSqJdgQgZCsZB48GHNR7tMceGILSWKNAzOGPCIB8KRmEiyqMRERNuxIkU+MZHljkaTXR6plEIB1KoumfYtF/cUXoym4S/BGI5uuUxvNYD8yu36bkwtbFiwgA4yWziZZuLzB4pWXiVZGTVlRmJzXtYtjmAbTs8O6lx1iWbIuPA2c8AoRcLmpQFzTn1CkrJ04

cl5NavCAGq16QlMDmU/plSI73mjk+epkBGlJxaanNpgF6qgS6fnQusEKmIXPugfyjgaXMDmdqign0/UUB3WbMdhmdlzMzalrzg67kcAK+EPTGKZKkH0Cq/zontXuxuZwEVfvKTGXBkHoznBI2TJe/CuZeW22W9QP5NytYRU8jcvgVAduADkjBU+OqA6691mzpSpbmTF05baw3G4gKbtQ04LcuELzbwv9uRXWCd2m13rqB0Krmd7jC1yo8B6d9e0P

uSRW3KaGMpg/uY/KBn9ORPqBk+lTLwGhva6M9Z8bLVVAee5Q95LyKpLFeQNprYDX4VdfP2xcbyhxD3BkNE0nuhzDs9kIkYSCLwEauREaAHoClRbyAhZ67zBQU7K4QCRR0b4DhoSCt7m4Z7W5ZA957IO797ca7JD7Goj65pj4ho+6T4r7R4b4h6bLz7h5L5T5r40F+q/I76e5p6H6d7H455n7ZAX7F6MAOqAYpaV736P6fTP5Wpv6+i4AlTFYPxKS

y7ARVaMKfy1bfz1bgDeKQC4BwBwBKhNLcA9TQCfSZAVAfikA9aFAMCEAIAUC1DCLoy8jvYSDUjSgeGeH9At4iAEyBg9D6BKg3bcIIz8LIybA+GkB+EBGOFoyiKuEQGSJfaSgRHYC+HRz+EZCxi/YKKqhQ7eFpFREZEBFBEmjA7ELTaRHREZClHEgQ55EA42GFHVH6BlRsxw4OgI5NHpHZCZH6CVxmLI4WKpE9FQB9Gxg/7Tw/QjFFG9EBETEIZVS

f7xAzEtFNzgEQDAGrHFE1FRCkBQBWRRFsBYG4DwFM5VE7H6A3i8iHEEgnFFwQDih3EFGjF9G3HHFsR9YVCiLeHMDYAEjygjRPBbi1YHBWzHCnBnDc7kz/Hkj4AACa3AcIcQ7OYwsI20MwrCNhRgbABgxhE45B2I/cP83RsxYxARbRhsDO6APxERXIJAH+6iliaODJPQW80xNh9JxAAAsmwEEtcbgJoMEH0oblYsfGItjKgE1hALUOSA8aQMoGyAA

BTLAbC8AbhJoamoB9yVAACUUoFUygdY4o3xipuAKpG0SalpvA1pOp+pJJpQzR0ctRCAAx5uuupQFYZOFUTYx84M+JFkWQgpwp3Az80BRA7JZypAtUgIp85hT80ZFWiBJUb8oZiZDpkAdg1QCA2AOQCop8cAvJ/Jp8QpMuopuhuZhAjAbEuJ+AAZgyXxqo6QlZnAfk0KpU+gnxXQjO3S+uwc5WkEJyVklZ1ZtZscnU4ADWkAxM4QxhHUIAHUQAA==
```
%%