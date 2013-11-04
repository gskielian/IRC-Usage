### try this blog

this is a great resource for getting started, I'll do my best to improve the steps below (installing xcode and command line tools seems a necessary but painful step though).

http://www.fizerkhan.com/blog/posts/Every-Programmer-should-use-IRC.html

### Setting up irssi:

1. Install XCode and Command Line Tools
2. Install HomeBrew with the following line
  * `ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"`
3. `brew install irssi`
4. type in to the command line `irssi`
5. wait for the prompt and type `/connect irc.freenode.net`
6. wait for the prompt and type `/join #yourfavoritechannel` --remember to include the hashtag before the channel name


### basic commands:

1. `/connect` - connects to node
  1. example: `/connect irc.freenode.net`  -- I like freenode
2. `/join` - joins a channel
  1. example: `/join #yourfavoritechannel`
3. `/nick` - changes nickname
  1. example: `/nick slayersboxer`
4. `/msg NickServ REGISTER password youremail@example.com` -- registers so that no one else can use your nickname (to use this you must have the desired username)
5. `/query yourPal` - begins private chat with yourPal
6. `/query yourPal` - ends private chat with yourPal (if already in private chat session)


References:

http://blog.jcuff.net/2013/05/brew-it-really-is-that-easy.html

http://quadpoint.org/articles/irssi/
