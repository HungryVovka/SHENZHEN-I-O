* **active** and **network** are simple outputs connected to LEDs.
* Control the **active** and **network** outputs with fixed, repeating signals as indicated in the verification tab.

```
MC4000 (active -> p0):
    mov 0 p0
    slp 6
    mov 100 p0
    slp 6
# why is this
# so hard? :(

MC4000 (network -> p0):
    mov 0 p0
    slp 4
    mov 100 p0
    slp 2
    mov 0 p0
    slp 1
    mov 100 p0
    slp 1
```
<details>
<summary>FAKE SURVEILLANCE CAMERA</summary>
<p>
  <img alt="Fake surveillance camera" src="https://github.com/HungryVovka/SHENZHEN-I-O/blob/main/FAKE%20SURVEILLANCE%20CAMERA/FAKE%20SURVEILLANCE%20CAMERA.jpg">
</p>
</details>
