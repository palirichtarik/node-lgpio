<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [lgpio](./lgpio.md) &gt; [gpioGetChipInfo](./lgpio.gpiogetchipinfo.md)

## gpioGetChipInfo() function

This returns information about a gpiochip.

**Signature:**

```typescript
export declare function gpioGetChipInfo(handle: number): GpioChipInfo;
```

## Parameters

<table><thead><tr><th>

Parameter


</th><th>

Type


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

handle


</td><td>

number


</td><td>

The GPIO device handle as returned by [gpiochipOpen()](./lgpio.gpiochipopen.md)


</td></tr>
</tbody></table>

**Returns:**

[GpioChipInfo](./lgpio.gpiochipinfo.md)

The GPIO chip info

