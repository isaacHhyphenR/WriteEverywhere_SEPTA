Add here **new folders** to be loaded as atlases from your mod. All them will be accessible in any layout in the game by using the pattern in `atlas` attribute in the xml:

> `atlas="YourModDllName:AtlasFolderName"`

Ensure that all your layout files are referring the atlas with your dll name as context. The atlases also will be available when editing layouts ingame

# Important notes:

- Each image have a transparent 1px row/line each side of the image to avoid bleeding when rendering. Consider that for atlases mounting dimension count purposes.
- The maximum image size is 1000x1000, each image.
- The maximum atlas size (i.e. all images combined) is 4096x4096.