# DICT-findfrequency


1) Find frequency

            def countFreq(nums):
                    dict = {}
                    for i in range(len(nums)):
                            key = nums[i]
                            if key not in dict:
                                    dict[key] = 1 
                                        # this is insert for the first time
                            else:
                                    dict[key] +=1
                    return dict

            print(countFreq([1,3,2,1,4,4,4])) 
            #{1: 2, 3: 1, 2: 1, 4: 3}
