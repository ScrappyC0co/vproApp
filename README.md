# vproApp



# InitContainer:
# That container will execute a command to remove lost+found folder,
# When that command complete vprodb container starts, and i will work.        
# Your container job is runnig the command that we have passed, and then complete,
# When this container is completed,exited, than the main container, vprodb container will start.

# vprodb-container:
# Then the main container, vprodb container will start, it will mount valid MYSQL,
# and there wont be anything in it.
# And MYSQL will start without any issues.