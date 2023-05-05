<h1 align="center">Hi 👋, I'm Tentoxa</h1>
<h3 align="center">A mostly backend developer out of Germany</h3>

```java
public class Profile extends GithubProfile {

    private boolean shouldFollow;
    private boolean shouldCheckRepositories;

    @Profile
    public void onLoad(){
        this.shouldFollow = true;
        this.shouldCheckRepositories = true;
        if(this.shouldFollow && this.shouldCheckRepositories){
            System.out.println("You are epic, thank you <3");
        }else{
            System.out.println("Thats ok! Enjoy your stay <3");
        }
    }

}
```
