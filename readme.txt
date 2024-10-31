=== Packaging Fit ===

Contributors:      tigriweb
Requires at least: 5.0
Tested up to:      6.6
Requires PHP:      7.4
Stable tag:        1.0.1
License:           GPLv2 or later
License URI:       https://www.gnu.org/licenses/gpl-2.0.html
Tags:              box, packer, packing, fit, packing-fit, woocommerce

Implementation of the “3D” bin packing/knapsack problem i.e. given a list of items, how many boxes do you need to fit them all in.

== Description ==

The Packaging Fit demo in the Playground tool is available [here](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/tigriweb/blueprints/master/packaging-fit/v1.1/blueprint.json).

Packaging Fit is a comprehensive WordPress plugin designed to assist users in optimizing the packaging of their products. Utilizing advanced 3D bin packing algorithms, Packaging Fit helps determine the most cost-effective way to pack items into boxes, minimizing shipping costs and maximizing space utilization. The plugin is seamlessly integrated with WooCommerce, providing powerful tools for e-commerce store owners to streamline their packing processes.

Benefits Recap:
- Time Savings: Automates the packing process, reducing time spent on manual packing.
- Cost Efficiency: Optimizes the number of boxes used, lowering shipping costs.
- Price Comparison: Compares different packing configurations to find the most cost-effective option.
- Fit Verification: Ensures products fit within chosen packaging, preventing repacking.
- Visual Guidance: Provides visual layouts to assist in arranging products, acting as a helpful suggestion rather than a rigid rule.

In summary, Packaging Fit is an essential tool for e-commerce businesses looking to improve their packing efficiency and reduce shipping costs. By leveraging its powerful algorithms and user-friendly features, businesses can ensure that their products are packed optimally, saving both time and money while maintaining high customer satisfaction.

== Frequently Asked Questions ==

= How can I test the plugin before using it on a live site? =

A demo of the Packaging Fit plugin is available in the [Playground tool](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/tigriweb/blueprints/master/packaging-fit/v1.1/blueprint.json).

= Where can I find Packaging Fit documentation? =

For help setting up and configuring Packaging Fit, please refer to [our documentation](https://tigriweb.gitbook.io/packaging-fit).

= Why should I use Packaging Fit? =

Packaging Fit significantly reduces the time and effort required to pack orders by automating the packing process. This ensures each package is packed as efficiently as possible, saving valuable time and reducing shipping costs. Additionally, Packaging Fit offers features like shipping cost comparison, fit verification, and visual packing assistance to further optimize your packaging process.

= How does Packaging Fit calculate free space? =

Free space is calculated by adding the specified free space value from each side of the package or product. For example, if you have a package with dimensions of 10x10x10 cm and you add 1 cm of free space, the actual internal dimensions will be 8x8x8 cm because 1 cm is added to each side, resulting in a total of 2 cm reduction. The same principle applies to products, ensuring that there is sufficient space around each item for optimal packing.

= What happens if I don't specify free space or rotation for a product? =

If you do not specify free space or rotation settings for a product, Packaging Fit will use the global settings. This ensures that all products are packed efficiently even if individual settings are not provided.

= Can Packaging Fit help me compare shipping costs? =

Yes, Packaging Fit allows you to compare shipping costs across different packing configurations. By providing detailed packing solutions, the plugin helps you choose the most economical option for shipping your products, reducing overall shipping expenses.

= How does the visual packing assistance work? =

Packaging Fit provides visual representations of how products can be arranged within a box using advanced packing algorithms. These visual layouts serve as helpful suggestions rather than strict guidelines, offering a starting point for packers to optimize the packing process. Manual adjustments can be made to achieve an even better fit, ensuring that the packing process is as efficient as possible.

= What should I do if I encounter an issue with the plugin? =

If you encounter an issue with Packaging Fit, you can follow these steps to describe the error and seek support:
1. Include the exact error message received.
2. Describe the steps taken leading up to the error.
3. Explain what you expected to happen and what actually happened.
4. Attach any relevant screenshots.
5. Provide details about your WordPress version, PHP version, and plugin versions.
6. Specify the browser and its version you are using.
By providing detailed and clear information, you help the support team diagnose and resolve the problem more efficiently.

= How can I add translations to Packaging Fit? =

You can find this information [here](https://tigriweb.gitbook.io/packaging-fit/translation).

= How does Packaging Fit integrate with WooCommerce? =

Packaging Fit integrates seamlessly with WooCommerce, enhancing the order fulfillment process with efficient packing solutions. You can add custom fields for free space and rotation to WooCommerce products, and use the Packaging Fit metabox on the order edit page to optimize the packing of order items.

= What are the benefits of using Packaging Fit? =

The benefits of using Packaging Fit include:
- Time savings through automated packing processes.
- Cost efficiency by optimizing the number of boxes used.
- Ability to compare different packing configurations to find the most cost-effective option.
- Ensuring products fit within chosen packaging, preventing repacking.
- Providing visual layouts to assist in arranging products, offering helpful suggestions for optimal packing.

== Changelog ==

= [1.0.1] 2024-10-11 =

* Feature - Update readme with Playground Demo URL.
* Fix - Replaced `wp_remote_get` with `wp_remote_post` to ensure compatibility with Playground.

= [1.0.0] 2024-07-02 =

Initial release