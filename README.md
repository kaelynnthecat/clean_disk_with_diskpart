# How to clean a disk with DiskPart
diskpart<br>
list disk<br>
select disk<br>
clean<br>
create partition primary<br>
format fs=ntfs quick | format fs=fat32 quick<br>
assign<br>
exit
