1. run cmd as admin
2. delete linux partitions and recapture using extend
3. run diskpart
4. list disk
5. select disk (usually there's one disk, disk 0 - with system storage)
6. select disk 0
7. list partition
8. select system partition (usually partition 2, labeled "System", approx 100mb)
9. select partition 2
10. assign letter=x
11. exit from diskpart
12. exec "x:"
13. exec "dir"
14. cd "efi"
15. exec "dir"
16. rd "<linux>" /s
17. Y
18. check again with "dir"
19. exit from cmd
20. restart
