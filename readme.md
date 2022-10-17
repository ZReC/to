# URL redirector

The idea is to be able to edit the redirection of an image (for example) if its host stops working.

## Base64 names
The [urls](./urls) folder contains files of 6-character long randomly generated names

Currently the valid characters are [A-Z][a-z][0-9][_][-]. I might add more in the future just for fun 🎈

A name can be generated [here](https://zrec.github.io/to/rng.htm).

## Examples

This should redirect to github.com
> https://zrec.github.io/to?6_V-io

Here is another example:

<svg height="10em" viewBox="0 0 27 27" stroke="none">
	<rect width="100%" height="100%" fill="#FFFFFF"/>
	<rect width="100%" height="100%" fill="#FFFFFF"/>
	<path d="M1,1h1v1h-1z M2,1h1v1h-1z M3,1h1v1h-1z M4,1h1v1h-1z M5,1h1v1h-1z M6,1h1v1h-1z M7,1h1v1h-1z M10,1h1v1h-1z M11,1h1v1h-1z M12,1h1v1h-1z M17,1h1v1h-1z M19,1h1v1h-1z M20,1h1v1h-1z M21,1h1v1h-1z M22,1h1v1h-1z M23,1h1v1h-1z M24,1h1v1h-1z M25,1h1v1h-1z M1,2h1v1h-1z M7,2h1v1h-1z M9,2h1v1h-1z M10,2h1v1h-1z M11,2h1v1h-1z M12,2h1v1h-1z M14,2h1v1h-1z M15,2h1v1h-1z M17,2h1v1h-1z M19,2h1v1h-1z M25,2h1v1h-1z M1,3h1v1h-1z M3,3h1v1h-1z M4,3h1v1h-1z M5,3h1v1h-1z M7,3h1v1h-1z M9,3h1v1h-1z M12,3h1v1h-1z M13,3h1v1h-1z M15,3h1v1h-1z M17,3h1v1h-1z M19,3h1v1h-1z M21,3h1v1h-1z M22,3h1v1h-1z M23,3h1v1h-1z M25,3h1v1h-1z M1,4h1v1h-1z M3,4h1v1h-1z M4,4h1v1h-1z M5,4h1v1h-1z M7,4h1v1h-1z M9,4h1v1h-1z M10,4h1v1h-1z M12,4h1v1h-1z M16,4h1v1h-1z M17,4h1v1h-1z M19,4h1v1h-1z M21,4h1v1h-1z M22,4h1v1h-1z M23,4h1v1h-1z M25,4h1v1h-1z M1,5h1v1h-1z M3,5h1v1h-1z M4,5h1v1h-1z M5,5h1v1h-1z M7,5h1v1h-1z M10,5h1v1h-1z M11,5h1v1h-1z M12,5h1v1h-1z M15,5h1v1h-1z M17,5h1v1h-1z M19,5h1v1h-1z M21,5h1v1h-1z M22,5h1v1h-1z M23,5h1v1h-1z M25,5h1v1h-1z M1,6h1v1h-1z M7,6h1v1h-1z M11,6h1v1h-1z M14,6h1v1h-1z M19,6h1v1h-1z M25,6h1v1h-1z M1,7h1v1h-1z M2,7h1v1h-1z M3,7h1v1h-1z M4,7h1v1h-1z M5,7h1v1h-1z M6,7h1v1h-1z M7,7h1v1h-1z M9,7h1v1h-1z M11,7h1v1h-1z M13,7h1v1h-1z M15,7h1v1h-1z M17,7h1v1h-1z M19,7h1v1h-1z M20,7h1v1h-1z M21,7h1v1h-1z M22,7h1v1h-1z M23,7h1v1h-1z M24,7h1v1h-1z M25,7h1v1h-1z M9,8h1v1h-1z M12,8h1v1h-1z M17,8h1v1h-1z M1,9h1v1h-1z M7,9h1v1h-1z M9,9h1v1h-1z M10,9h1v1h-1z M11,9h1v1h-1z M14,9h1v1h-1z M16,9h1v1h-1z M17,9h1v1h-1z M18,9h1v1h-1z M19,9h1v1h-1z M22,9h1v1h-1z M23,9h1v1h-1z M24,9h1v1h-1z M1,10h1v1h-1z M2,10h1v1h-1z M4,10h1v1h-1z M5,10h1v1h-1z M6,10h1v1h-1z M9,10h1v1h-1z M11,10h1v1h-1z M12,10h1v1h-1z M13,10h1v1h-1z M16,10h1v1h-1z M18,10h1v1h-1z M20,10h1v1h-1z M21,10h1v1h-1z M22,10h1v1h-1z M23,10h1v1h-1z M1,11h1v1h-1z M2,11h1v1h-1z M3,11h1v1h-1z M6,11h1v1h-1z M7,11h1v1h-1z M8,11h1v1h-1z M10,11h1v1h-1z M16,11h1v1h-1z M17,11h1v1h-1z M18,11h1v1h-1z M19,11h1v1h-1z M24,11h1v1h-1z M25,11h1v1h-1z M1,12h1v1h-1z M5,12h1v1h-1z M9,12h1v1h-1z M10,12h1v1h-1z M11,12h1v1h-1z M15,12h1v1h-1z M16,12h1v1h-1z M17,12h1v1h-1z M18,12h1v1h-1z M19,12h1v1h-1z M21,12h1v1h-1z M22,12h1v1h-1z M2,13h1v1h-1z M3,13h1v1h-1z M4,13h1v1h-1z M7,13h1v1h-1z M10,13h1v1h-1z M11,13h1v1h-1z M17,13h1v1h-1z M19,13h1v1h-1z M20,13h1v1h-1z M22,13h1v1h-1z M24,13h1v1h-1z M25,13h1v1h-1z M1,14h1v1h-1z M4,14h1v1h-1z M6,14h1v1h-1z M10,14h1v1h-1z M13,14h1v1h-1z M14,14h1v1h-1z M16,14h1v1h-1z M20,14h1v1h-1z M24,14h1v1h-1z M1,15h1v1h-1z M3,15h1v1h-1z M5,15h1v1h-1z M7,15h1v1h-1z M9,15h1v1h-1z M11,15h1v1h-1z M14,15h1v1h-1z M16,15h1v1h-1z M17,15h1v1h-1z M19,15h1v1h-1z M23,15h1v1h-1z M24,15h1v1h-1z M25,15h1v1h-1z M1,16h1v1h-1z M3,16h1v1h-1z M4,16h1v1h-1z M9,16h1v1h-1z M11,16h1v1h-1z M13,16h1v1h-1z M16,16h1v1h-1z M20,16h1v1h-1z M21,16h1v1h-1z M23,16h1v1h-1z M1,17h1v1h-1z M4,17h1v1h-1z M7,17h1v1h-1z M8,17h1v1h-1z M10,17h1v1h-1z M11,17h1v1h-1z M13,17h1v1h-1z M14,17h1v1h-1z M15,17h1v1h-1z M17,17h1v1h-1z M18,17h1v1h-1z M19,17h1v1h-1z M20,17h1v1h-1z M21,17h1v1h-1z M22,17h1v1h-1z M23,17h1v1h-1z M9,18h1v1h-1z M15,18h1v1h-1z M17,18h1v1h-1z M21,18h1v1h-1z M22,18h1v1h-1z M23,18h1v1h-1z M24,18h1v1h-1z M1,19h1v1h-1z M2,19h1v1h-1z M3,19h1v1h-1z M4,19h1v1h-1z M5,19h1v1h-1z M6,19h1v1h-1z M7,19h1v1h-1z M11,19h1v1h-1z M13,19h1v1h-1z M15,19h1v1h-1z M17,19h1v1h-1z M19,19h1v1h-1z M21,19h1v1h-1z M22,19h1v1h-1z M25,19h1v1h-1z M1,20h1v1h-1z M7,20h1v1h-1z M10,20h1v1h-1z M12,20h1v1h-1z M16,20h1v1h-1z M17,20h1v1h-1z M21,20h1v1h-1z M22,20h1v1h-1z M25,20h1v1h-1z M1,21h1v1h-1z M3,21h1v1h-1z M4,21h1v1h-1z M5,21h1v1h-1z M7,21h1v1h-1z M10,21h1v1h-1z M12,21h1v1h-1z M13,21h1v1h-1z M14,21h1v1h-1z M16,21h1v1h-1z M17,21h1v1h-1z M18,21h1v1h-1z M19,21h1v1h-1z M20,21h1v1h-1z M21,21h1v1h-1z M22,21h1v1h-1z M23,21h1v1h-1z M1,22h1v1h-1z M3,22h1v1h-1z M4,22h1v1h-1z M5,22h1v1h-1z M7,22h1v1h-1z M10,22h1v1h-1z M13,22h1v1h-1z M16,22h1v1h-1z M17,22h1v1h-1z M19,22h1v1h-1z M20,22h1v1h-1z M22,22h1v1h-1z M23,22h1v1h-1z M24,22h1v1h-1z M25,22h1v1h-1z M1,23h1v1h-1z M3,23h1v1h-1z M4,23h1v1h-1z M5,23h1v1h-1z M7,23h1v1h-1z M11,23h1v1h-1z M13,23h1v1h-1z M16,23h1v1h-1z M17,23h1v1h-1z M20,23h1v1h-1z M23,23h1v1h-1z M25,23h1v1h-1z M1,24h1v1h-1z M7,24h1v1h-1z M17,24h1v1h-1z M18,24h1v1h-1z M20,24h1v1h-1z M22,24h1v1h-1z M25,24h1v1h-1z M1,25h1v1h-1z M2,25h1v1h-1z M3,25h1v1h-1z M4,25h1v1h-1z M5,25h1v1h-1z M6,25h1v1h-1z M7,25h1v1h-1z M9,25h1v1h-1z M10,25h1v1h-1z M13,25h1v1h-1z M14,25h1v1h-1z M17,25h1v1h-1z M18,25h1v1h-1z M20,25h1v1h-1z M22,25h1v1h-1z M25,25h1v1h-1z" fill="#000000"/>
</svg>

## License

[See here](license.md)
