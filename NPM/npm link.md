# NPM link

We can use npm link to create symlinks for your local registry and be able to
use local dependencies.

To create the symlink go to your local package and use the next command:

```bash
$ sudo npm link
```

After creating the symlink go to your project and create the link to the local
package:

```bash
$ npm link <package-name>
```
