<script>
  import { Navbar, Page, List, ListItem, Block } from 'framework7-svelte';
</script>

<Page>
  <Navbar title="Routable Modals" backLink="Back" />
  <Block strong>
    <p>In addition to pages, Framework7 router allows to load modal components:</p>
  </Block>
  <List>
    <ListItem title="Popup" link="popup/" />
    <ListItem title="Action Sheet" link="actions/" />
  </List>
</Page>
