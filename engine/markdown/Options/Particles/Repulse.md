# Particles Repulse

| key                   | option type          | example          | notes                                                |
| --------------------- | -------------------- | ---------------- | ---------------------------------------------------- |
| `enable`              | `boolean`            | `true` / `false` |                                                      |
| `distance`            | `number`             | `100`            |                                                      |
| `duration`            | `number`             | `2`              |                                                      |
| `factor`              | `number`             | `1`              |                                                      |
| `speed`               | `number`             | `100`            | The rate in seconds at which a particle will disperse <br>from around the cursor at any given time. A <br> `repulse` speed of `0` will result in no effect <br> on the particles. |
| `value`               | `number`             | `50`             |                                                      |
| `random`              | `boolean` / `object` | `true` / `false` | If boolean it randomize the size from `0` to `value` |
| `random.enable`       | `boolean`            | `true` / `false` | This is the alternative to pure boolean value        |
| `random.minimumValue` | `number`             | `10`             | This is the minimum value used in random values      |
