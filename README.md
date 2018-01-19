# GitGo
A minimal CLI app to query GitHub users.

## Installation
- `go get github.com/guigo2k/gitgo`

## Usage
- Help:

    ```
    $ gitgo
    Usage: gitgo [options]
    Options:
        -u, --user string
            Search Users
    ```  

- Single User Query:

    ```
    $ gitgo -u guigo2k
    Searching user(s): [guigo2k]
    Username:        guigo2k
    Name:            Guigo2k
    Email:           guigo2k@guigo2k.com
    Bio:             DevOps Engineer
    ```

- Multi-User Query:

    ```
    $ gitgo -u guigo2k,tropicloud                                                                                                                                    
    Searching user(s): [guigo2k tropicloud]
    Username:        guigo2k
    Name:            Guigo2k
    Email:           guigo2k@guigo2k.com
    Bio:             DevOps Engineer

    Username:        tropicloud
    Name:            Tropicloud
    Email:           admin@tropicloud.net
    Bio:             Cloud Hosting Platform
    ```

## Contributing
Feel free to open a GitHub Issue or submit a PR with your features.
