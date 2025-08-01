<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [lgpio](./lgpio.md) &gt; [gpioSetSamplesFunc](./lgpio.gpiosetsamplesfunc.md)

## gpioSetSamplesFunc() function

This sets up a callback to be called when any alert GPIO changes state.

**Signature:**

```typescript
export declare function gpioSetSamplesFunc(callback: (alerts: GpioAlert[]) => void): void;
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

callback


</td><td>

(alerts: [GpioAlert](./lgpio.gpioalert.md)<!-- -->\[\]) =&gt; void


</td><td>

The callback function


</td></tr>
</tbody></table>

**Returns:**

void

## Remarks

Note that no handle or gpio is specified. The callback function will receive alerts for all gpiochips and gpio.

