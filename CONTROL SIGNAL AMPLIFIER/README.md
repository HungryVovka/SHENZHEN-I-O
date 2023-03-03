* **control-in** is a simple input connected to factory equipment.
* **control-out** is a simple output connected to other factory equipment.
* The signal from **control-in** should ne multiplied by 2 and copied to **control-out**.

```
MC4000 (control-in -> p0):
    mov 0 p0 acc
    mul 2
    mov acc p1
    slp 1
```
<details>
<summary>CONTROL SIGNAL AMPLIFIER</summary>
<p>
  <img alt="control signal amplifier" src="https://github.com/HungryVovka/SHENZHEN-I-O/blob/main/CONTROL%20SIGNAL%20AMPLIFIER/CONTROL%20SIGNAL%20AMPLIFIER.jpg">
</p>
</details>
