# <div align="center">Hi there, I'm Tentoxa! 👋</div>

```java
public class Profile extends GithubProfile {

    private boolean shouldFollow;
    private boolean shouldCheckRepositories;

    @Override
    public void onLoad(){
        this.shouldFollow = true;
        this.shouldCheckRepositories = true;
        if(this.shouldFollow && this.shouldCheckRepositories){
            System.out.println("You are epic, thank you <3");
        }else{
            System.out.println("Thats ok! Enjoy your stay!");
        }
    }

}
```

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Tentoxa&show_icons=true&theme=radical" alt="Tentoxa's GitHub Stats" />
</div>

