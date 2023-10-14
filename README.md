# Novoline-No-BoneMatrix
since kids are still crying to update this, i made it so u dont need bone matrix offset anymore. all u gotta update is a few vtables: post render, process event. i think thats all the vtables. then update static_find_object offset, i didnt test this but ik it should work

how it works:
this will use GetSocketLocation, this function doesnt use bone ids, so we will have to call GetBoneName inside of SkinnedMeshComponent to get the bone name within the index. i dont need credits its just a kinda good and bad source

what to update ( CONFIRMED ):
static find object
mesh ( RARELY CHANGES )
process_event
post_render

what needs to be updated ( 10/13/2023 )
i think only these:
post_render
static find object
