# merge-sort-project

*[16,21,11,8,12,22] -> Merge Sort
1)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.

Answer of 1 => We should select a middle point every step.tThis lead to us ease about find the number that we want to find.
                                           [16,21,11,8,12,22]
                                    [16,21,11]           [8,12,22]
                                 [16]     [21,11]      [8]     [12,22]
                            [16]        [21]   [11]    [8]   [12]   [22]
                            [16]         [11,21]       [8]    [12,22]
                                [11,16,21]               [8,12,22]
                                        [8,11,12,16,21,22]
Answer of 2 =>2^x=n , x=logn  each step you covered logn number and there are n step so big o notation is O(n.logn)                                    
