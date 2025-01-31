<p align="center">
<img src="https://i.imgur.com/Aja9D5E.jpeg" />
</p>

<h1>VirtualBox - Snapshot Management</h1>
Snapshots allow you to preserve a specific state of the virtual machine. This is particularly useful when experimenting with system changes or updates. <br />

<h2>Environments and Technologies Used</h2>

- VirtualBox
- VirtualBox Extension Pack
- Ubuntu

<h2>Operating System Used</h2>

- Linux

<h2>Prerequisites</h2>

- 2GB of RAM minimum (4GB recommended)
- Multicore processor
- Sufficient hard drive space (the amount depends on your virtual machine usage)

<h2>Managing Snapshots</h2>
<p>
<img src="https://i.imgur.com/vT6LSZJ.png" />
<img src="https://i.imgur.com/pCcdMqA.png" />
</p>
<p>
Open VirtualBox and select the virtual machine you want to manage. Navigate to the **Snapshots** tab, located in the top panel.
Click the **Take** button to create a new snapshot. Provide a descriptive name and optional comments. 
</p>

<p>
<img src="https://i.imgur.com/avwR47C.png" />
</p>

<p>
For example, you can name the snapshot **Pre-Update Configuration** to signify that this snapshot was created before applying updates. Snapshots preserve the complete state of your virtual machine, including running applications, settings, and data.
</p>

<p>
<img src="https://i.imgur.com/4jA5zEa.png" />
</p>

<p>
To restore a snapshot, navigate back to the **Snapshots** tab and select the snapshot you wish to restore. Click the **Restore** button. Restoring a snapshot will revert the virtual machine to the state it was in when the snapshot was taken. Be cautious, as any changes made after the snapshot will be lost unless you take a new snapshot before restoring.
</p>

<p>
You can also delete older snapshots to free up disk space. Right-click on the snapshot and select **Delete Snapshot**. Deleting a snapshot will not delete your virtual machine but will remove the ability to revert to that particular state.
</p>
