
# Android Resource Naming Conventions

To maintain a clear, organized, and manageable project structure, follow these naming conventions for various types of resources in Android:

## 1. String Resources

**Screen-Specific:**

| Screen                | String         | Resource Name                 |
|-----------------------|----------------|-------------------------------|
| Registration Fragment | “Register now” | `registration_register_now`   |
| Sign Up Activity      | “Cancel”       | `sign_up_cancel`              |
| Rate App Dialog       | “No thanks”    | `rate_app_no_thanks`          |

**General Prefix Rules:**

| Prefix  | Description                                 | Example                       |
|---------|---------------------------------------------|-------------------------------|
| error_  | Used for error messages                     | `error_network`               |
| title_  | Used for dialog titles                      | `title_confirmation`          |
| action_ | Used for option menu actions                | `action_settings`             |
| msg_    | Used for generic messages in dialogs        | `msg_loading`                 |
| label_  | Used for activity labels                    | `label_user_profile`          |
| button_ | Used for button text                        | `button_submit`               |
| hint_   | Used for hints                              | `hint_username`               |
| desc_   | Used for image descriptions                 | `desc_profile_picture`        |

## 2. Layout Resources

| Resource Type         | Prefix            | Example                       |
|-----------------------|-------------------|-------------------------------|
| Activity Layouts      | `activity_`       | `activity_main.xml`           |
| Fragment Layouts      | `fragment_`       | `fragment_home.xml`           |
| List Item Layouts     | `item_`           | `item_product.xml`            |
| Dialog Layouts        | `dialog_`         | `dialog_confirmation.xml`     |
| Custom Views          | `view_`           | `view_header.xml`             |


## 3. Drawable Resources

| Asset Type    | Prefix          | Example                       |
|---------------|------------------|-------------------------------|
| Action bar    | `ab_`            | `ab_stacked.9.png`            |
| Button        | `btn_`           | `btn_send_pressed.9.png`      |
| Dialog        | `dialog_`        | `dialog_top.9.png`            |
| Divider       | `divider_`       | `divider_horizontal.9.png`    |
| Icon          | `ic_`            | `ic_star.png`                 |
| Menu          | `menu_`          | `menu_submenu_bg.9.png`       |
| Notification  | `notification_`  | `notification_bg.9.png`       |
| Tabs          | `tab_`           | `tab_pressed.9.png`           |

## 4. Color Resources

| Resource Type    | Prefix          | Example                       |
|------------------|-----------------|-------------------------------|
| Primary Colors   | `color_primary` | `color_primary`               |
| Accent Colors    | `color_accent`  | `color_accent`                |
| Other Colors     | `color_`        | `color_background`            |

## 5. Dimension Resources

| Resource Type    | Prefix          | Example                       |
|------------------|-----------------|-------------------------------|
| General Dimensions| `dim_`         | `dim_margin_small`            |
| Text Sizes       | `text_size_`    | `text_size_title`             |

## 6. Style Resources

| Resource Type    | Prefix                  | Example                       |
|------------------|-------------------------|-------------------------------|
| Themes           | `Theme.`                | `Theme.App`                   |
| Widget Styles    | `Widget.<Component>`    | `Widget.Button.Primary`       |

## 7. ID Resources

| Resource Type    | Prefix            | Example                       |
|------------------|-------------------|-------------------------------|
| View IDs         | `@+id/`           | `@+id/button_submit`          |

## 8. Menu Resources

| Resource Type    | Prefix            | Example                       |
|------------------|-------------------|-------------------------------|
| Menu Files       | `menu_`           | `menu_main.xml`               |
| Menu Items       | `menu_`           | `menu_settings`               |

## 9. Animation Resources

| Resource Type    | Prefix            | Example                       |
|------------------|-------------------|-------------------------------|
| Animations       | `anim_`           | `anim_slide_in.xml`           |

## 10. XML Resources

| Resource Type    | Prefix            | Example                       |
|------------------|-------------------|-------------------------------|
| XML Files        | `xml_`            | `xml_preferences.xml`         |

## General Guidelines

1. **Consistent Prefixes:** Ensure that each resource type has a consistent and descriptive prefix.
2. **Descriptive Names:** Use clear and descriptive names for each resource to indicate its purpose and state.
3. **Separate Words with Underscores:** Use underscores to separate different parts of the name for readability.
4. **Avoid Abbreviations:** Use full words to maintain clarity unless commonly abbreviated (e.g., `btn` for button).
5. **Screen-Specific Prefixes:** Include the screen or feature name as a prefix for string resources to avoid conflicts and improve clarity.
