## An example of usage of the script:

```lua
newimagefromdata(
  Instance.new(
    "ScreenGui",
    game:GetService("Players"):GetPlayers()[1].PlayerGui
  ),
  10,
  10,
  UDim2.new(
    0.5,
    -10,
    0.5,
    -5
  ),
  {
    {
      1,
      1,
      Color3.new(1, 0, 0)
    },
    {
      2,
      1,
      Color3.new(
        0,
        0,
        1
      )
    }
  }
)
```