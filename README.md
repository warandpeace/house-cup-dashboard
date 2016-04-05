# house-cup-dashboard

A simple dashboard for a Harry Potter House Cup at an upcoming house party.


## admin.html

Super basic admin application with no formatting. Should have a simple interface to allow someone (me)
to use their mobile phone to update the point totals by posting to the Point Storage JSON endpoint.

## index.html

The dashboard! This will be what everyone sees. Should show current point totals & an an ideal world
would also a) dynamically update when points are added to the JSON endpoint and b) play some kind of
animation of that house's logo fullscreened.

## main.css

Main css for the dashboard, contains everything needed to make this look hella pretty.

## Point Storage

Points are currently stored in a totally unsecured JSON endpoint courtesy of Dweet.io

Integrate against https://dweet.io/get/latest/dweet/for/warandpeace-house-cup-dashboard

```
{
  "this": "succeeded",
  "by": "getting",
  "the": "dweets",
  "with": [
    {
      "thing": "warandpeace-house-cup-dashboard",
      "created": "2016-04-05T04:28:47.858Z",
      "content": {
        "gryffindor": {
          "points": "0"
        },
        "hufflepuff": {
          "points": "0"
        },
        "ravenclaw": {
          "points": "0"
        },
        "slytherin": {
          "points": "0"
        }
      }
    }
  ]
}
```