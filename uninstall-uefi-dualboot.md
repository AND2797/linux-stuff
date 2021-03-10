1. run cmd as admin
2. delete linux partitions and recapture using extend
3. run diskpart
4. list disk
5. select disk (usually there's one disk, disk 0 - with system storage)
6. select disk 0
7. list partition
8. select system partition (usually partition 2, labeled "System", approx 100mb)
9. assign letter=x
10. exit from diskpart
11. exec "x:"
12. exec "dir"
13. cd "efi"
14. exec "dir"
15. rd "<linux>" /s
16. Y
17. check again with "dir"
18. exit from cmd
29. restart
