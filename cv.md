1. Name: Yurii Velidchenko.
2. Contact Info:
    * *e-mail*: velidoss11@gmail.com
    * *telegram*: @Velidoss
3. About me:
    I am motivated, positive man, who wants to witness the world of programming. Today my goal is to master my javascript skills to became React developer. Besides my work, I code every day, read articles on habr, medium, and trying to learn something new. 
4. Skills:
    * *languages:* JavaScript, PHP;
    * *Frameworks&libraries:* React, Redux, axios, meterial UI
    * *Version control:* git

5. Latest code examples:
    ```javascript
    export const moviesAPI={
        queryMovies:(sortType, page)=>{
            return instance.get(`/discover/movie?&sort_by=${sortType}&page=${page}`).then(response=>{
                return response.data;
            });
        },
        queryPopularMovies:(page)=>{
            return instance.get(`/movie/popular?page=${page}`).then(response=>{
                return response.data;
            });
        }
    }
    ```
6. Experience:
    Today I have few pet-projects as:
    * [Todo-app](https://github.com/Velidoss/Task-manager) on React hooks, deployed on firebase . You can add todos, correct them, mark todo as "completed" or "cancelled".
    * [Movie app](https://github.com/Velidoss/MovieApp), created with React, Redux,with  axios data access layer for TMDB API . Big library of films, tv-shows, actors, playlists, where user can create his own watchlists, rate movies and tv-shows.http://github.com - automatic!
    
7. Education:
    Kiev Polytechnic Institute.
    Currently, Ia self-taught programmer
8. English : Intermediate B1 . 
    Experience of business intercourse and working with english documentation.