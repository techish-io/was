# was-cookbook

The wlp cookbook installs and configures the WebSphere Application Server

## Supported Platforms

Redhat

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['was']['version']</tt></td>
    <td>int</td>
    <td>default was version</td>
    <td><tt>8.5</tt></td>
  </tr>
</table>

## Usage

### was::default

Include `was` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[was::default]"
  ]
}
```

## Contributing

1. Fork the repository on Github
2. Create a named feature branch (i.e. `add-new-recipe`)
3. Write you change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request

## License and Authors

Author:: Ishtiaq Ahmed (ishtiaq@techish.com)
