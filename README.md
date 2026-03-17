# clean_disk_with_diskpart
diskpart 
list disk
select disk
clean
format fs=ntfs quick | format fs=fat32 quick
assign
exit
