| values | At launch | initial | final    |
| ------ | --------- | ------- | -------- |
| m      | $m_0$     | $m$     | $m - dm$ |
| t      | 0         | $t$     | $t + dt$ |
| v      | 0         | $v$     | $v + dv$ |

at initial and final, there is $Vg$ acting downwards

$dm$ = amount of fuel burnt
$$mv = (m - dm)(v + dv) + dm(-Vg)$$
$$Vgdm + vdm = mdv$$
$$dm(V + Vg) = mdv$$
Relative [[velocity]] $= V + Vg = u$

Since the direction of resultant [[velocity]] is against gravity, it is $-u$

$$mdv = -udm$$
$$\int_{v_0}^{v} dv = \frac{-u}{m} \int_{m_0}^{m} dm$$
$$v - v_0 = -u \log_e (m - m_0)$$
$$v - v_0 = -u log_e m - log_e m_0$$
$$v - v_0 = -u \log_e\frac{m}{m_0}$$
$$v - v_0 = u \log_e \frac{m_0}{m}$$
Since $V_0 = 0$ at the start,
$$\therefore v = u \log_e \frac{m0}{m}$$

## [[Force]]

$$m \frac{dv}{dt} = -u \frac{dm}{dt}$$
Since $\frac{dv}{dt} = a$

$$ma = -u \frac{dm}{dt}$$
Since $F = ma$
$$ F = -u \frac{dm}{dt}$$
## Considering gravitation,
The Net [[Force]] would be:
$$ma = F - mg$$
$$ma = -u \frac{dm}{dt} - mg$$
$$a = \frac{u}{m} \frac{dm}{dt} - g$$
Since $m = m_0 - t \frac{dm}{dt}$
$$a = \frac{u}{m_0 - t\frac{dm}{dt}} \frac{dm}{dt} - g$$