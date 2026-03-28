# Step 1 : Change unit to milimeters

- In scene properties (just above 'world') go to `"Unit"`
- Ensure `"Unit System"` is set to `Metric`
- Change `"Length"` from `Meters` to `Milimeters`
- Change `"Unit Scale"` to `0.001`

# Step 2 : Get the grid back

After step & the grid has disareared because the grid is still in meters

- In the top icons (Next to the "Viewport Shading : Solid/Wireframe/Rendered") select the Viewport Overlays
- Change `"Scale"` to `0.001`

# Step 3 : Change the View settings

- Hit `"N"` to show the side options
- Under `"View"` Change the `"End"` from `1000 mm` to `10000 mm` (avoid the view to clip past 10cm)

# Step 4 : Clean the Scene

- Delete the light source
- Delete the camera