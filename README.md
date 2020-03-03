# Jenkins

There are many Jenkins like this, but this one is mine.

## Usage

`docker-compose up` to get Jenkins running.
`docker exec -it <container-id> bash` to access the shell. (Not the same as SSH).

## References

* [Something on StackOverflow][1]
* [Volumes documentation][2]
* [Migrating volumes][3]
* [Old Medium Blogpost on setup][4]
* [How to access a container's the shell][5]



 [1]: https://stackoverflow.com/questions/46167844/how-to-configure-a-dockerfile-and-docker-compose-for-jenkins
 [2]: https://docs.docker.com/storage/volumes/
 [3]: https://bobcares.com/blog/move-docker-container-to-another-host/
 [4]: https://medium.com/@Joachim8675309/jenkins-environment-using-docker-6a12603ebf9
 [5]: https://stackoverflow.com/questions/30172605/how-do-i-get-into-a-docker-containers-shell
