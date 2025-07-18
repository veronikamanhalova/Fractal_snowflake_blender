# Fractal snowflakes
Snowflake models using LSystem node in Blenders Animation nodes editor.

## Used algorithms
With each snowflake I used the LSystem node. In text list node made new rule using IFS (iterated function systems) Koch curve rules for repetive expresion. This expresion was then repeated by the LSystem in N generations resulting in one part of the showflake.

In Koch curve rules F means forward line, + means rotate line in positive direction and - in the negative direction.

Next I made triangular tube mesh from the mesh info produced by LSystem node and repeated the pattern of the snowflake 6 times to produce a model of the snowflake.

Lastly added some Planes to make a box around the snowflake and created glowing material.

## Snowflake n.1
![alt text](snowflake1/snowflake.png)
![alt text](snowflake1/animation_nodes.png)

## Snowflake n.2
![alt text](snowflake2/snowflake.png)
![alt text](snowflake2/animation_nodes.png)

## Snowflake n.3
![alt text](snowflake3/snowflake.png)
![alt text](snowflake3/animation_nodes.png)

## Snowflake n.4
![alt text](snowflake4/snowflake.png)
![alt text](snowflake4/animation_nodes.png)
