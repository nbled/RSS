# RSS
Simple class to parse RSS.

## Exemple of usage:
    require_once("parser.class.php");
    require_once("templates.class.php");

    use RSS;

    $obj = new RSS\RSSParser(new RSS\DefaultRSSTemplate);
    $obj->feed("https://kalaxia.org/?feed=rss2");

    var_dump($obj);
