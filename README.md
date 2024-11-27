# VRChat Outfit Helper

A Blender add-on designed to streamline the process of transferring vertex groups and armatures between objects, specifically useful for VRChat model preparation.

## Features

- **Transfer Vertex Groups:** Easily transfer vertex groups and armatures from an active object to a selected object.
- **Delete Unused Vertex Groups:** Remove vertex groups with no weight assignments from the active object.
- **Delete Unused Bones:** Clean up armatures by deleting bones not associated with any vertex group. Optionally, duplicate the armature before modifications.

## Installation

1. Download the `VRChat Outfit Helper` add-on script.
2. Open Blender and go to `Edit > Preferences > Add-ons`.
3. Click `Install...` and select the downloaded zip file.
4. Enable the add-on by checking the box next to `VRChat Outfit Helper`.

## How to Use

1. **Transfer Vertex Groups:**
   - Select two objects: the source (active) and target (selected).
   - Go to `Object > Vertex Groups > VRChat Outfit Helper`.
   - Choose **Transfer Vertex Groups from Active Object**.

2. **Delete Unused Vertex Groups:**
   - Select an object with vertex groups.
   - Go to `Object > Vertex Groups > VRChat Outfit Helper`.
   - Choose **Delete Unused Vertex Groups** to clean up zero-weight groups.

3. **Delete Unused Bones:**
   - Select an object with vertex groups parented to an armature.
   - Go to `Object > Vertex Groups > VRChat Outfit Helper`.
   - Choose **Delete Unused Bones** and confirm the operation.

## Menu Location

You can find the add-on functionality under:
`Object > Vertex Groups > VRChat Outfit Helper`

## Requirements

- Blender 4.2 or newer.
