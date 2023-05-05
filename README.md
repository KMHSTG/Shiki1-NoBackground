# **Shikigami no Shiro - No Background**

Patch that removes the always-visible background artwork, which the game doesn't allow you to turn off. This leaves just the central playing area with nothing around it. Works both in normal screen orientation (black bars on the sides) and rotated (black bars above and below). All the UI style options work fine as well, though this was made specifically to be used with the "Classic" arcade-style UI.

Note that this patch is for the Steam version (also called "Castle of Shikigami"), not the earlier PC release of the game.

## Patching Instructions:

1 - From the installed Shikigami no Shiro folder (the one where Shikigami.exe is), go to \data.

2 - Using your xdelta patcher of choice, apply the shiki1-nobg.xdelta patch to the file named "pack4.pack". Make sure that your patched file has the same filename as the original.
  
##### NOTE 1: Keeping a backup of both the original and patched pack4.pack is a good idea, so they can be switched out whenever. But also because Steam at some point, might randomly decide, to revert the patched file back to the original state.

##### NOTE 2: The patching process can be verified with the hashes below:
  
pack4.pack

(Original) &nbsp; CRC32:&nbsp; cf7b9ea8  
(Original) &nbsp; MD5:  &nbsp; &nbsp;   3b5f12ab09fda7ef20408ace92db4daa  
(Original) &nbsp; SHA-1: &nbsp; 7908e2aeb1eb8c85238db7ae7de13cbc5a0d4e58  
  
(Patched) &nbsp; CRC32:&nbsp; 7f1ae520  
(Patched) &nbsp; MD5:  &nbsp; &nbsp;   5e54e6af4fc208d776fb6684c227afeb  
(Patched) &nbsp;  SHA-1: &nbsp; 9632b93597e320b32cec7129817975036e17285c  

## &nbsp;

Patch by KMH  
2023-05-02 - Released
